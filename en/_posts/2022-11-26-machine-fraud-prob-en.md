---
title: Probability of fraud detection in the machine vote control count 
date: 2022-11-26 00:00:00
description: How many polling stations should be checked to detect vote manipulation hidden in the machine code?
featured_image: /assets/img/elections.png
author: Nikola Tulechki, Laura Tolosi
lang: en
use_math: true
---

*While the style of this post is tongue-in-cheek, it seriously illustrates how even a minimal sampling of notes from the 
voting machines would detect a hidden attempt at vote manipulation in the software*

Let's play the following scenario: 
Theo has unrestricted access to the code of the voting machines.
He's skillful enough to be able to rewrite it so that he can do whatever he wants.
He is determined to take malicious advantage of this access,
in order to improve the result of his beloved party (LB).

Theo will add a few lines of code to "nudge up" the *LB* score by ten percent. 
To do this, each machine would have to automatically replace the vote of every tenth voter
and record one more vote for LB instead of the party they voted for. 

So far so good, but Theo knows that in addition to the memory entry, the machine also prints out a note,  
which the voter drops into the box. 
If he looks at it and it says *LB* instead of the party he really voted for, 
he'll complain to the committee members and the replacement plan will fail.

So Theo decides to instruct the machine to print out a note with the voter's real vote, but to record a vote for *LB* in memory. 
Thus the voter is successfully fooled and 
to detect the fraud, the notes in the box must be compared with the data in the machine's memory.

Theo knows that such an examination won't be performed in all sections, so he decides to calculate the probability of
his manipulation being detected when a given number of sections are randomly examined. 
Obviously if every machine is compromised the probability is 100%,
because even if one section is examined, 
the difference between the protocol and the notes will be detected.

*However, is there any way to add a condition in the code,
that would reduce the number of machines that have been manipulated so that the probability of being detected on inspection is acceptably small..* 

Theo is naturally very good at math (as well as at Google search). He quickly finds the answer to his question in 
[this post](https://math.stackexchange.com/questions/1680387/at-least-k-successes-in-n-tries-without-replacement){:target="_blank"} on StackExchange.

Theo learns that the distribution of selected elements (in this case compromised sections) in a random sample without repetition is hypergeometric.
It can be calculated with the following equation

$\mathsf P(W=k) = \dfrac{\dbinom{K}{k}~\dbinom{N-K}{n-k}}{\dbinom{N}{n}} \qquad \Big[0\leq k\leq \min(K, n) \leq \max(K, n) \leq N\Big]$


Където:

* $N$ is the population size (total number of sections = 13000) 
* $K$ is the total number of selected elements (compromised sections)
* $n$ is the sample size
* $k$ is the number of selected items in the sample (in this case 0)  
* $P(W=k)$ is the probability of having $k$ elements in the sample

Theo doesn't even have to calculate it by hand. 
He can use this hypergeometric calculator, 
to calculate the different scenarios:

<script type="text/javascript" id="WolframAlphaScriptab7e3f4ceba7f23947ef49a3bbf93b56" src="//www.wolframalpha.com/widget/widget.jsp?id=ab7e3f4ceba7f23947ef49a3bbf93b56"></script>

Theo is a risk taker and decides to check on the number of machines necessary to ensure that the probability of getting caught is smaller than the probability not to be caught 
or $P(W=k)>0.5$.  

Here are the results:

* With 10% sampling control, $K=1300$ the maximum number of sections he can manipulate is *6*
* With 5% sample control, $K=650$ the maximum number of sections is *14*
* Even if only 1% of sections are examined $K=130$, if Theo manipulates more than *70* sections, the probability of getting caught is greater than 50%  

Theo is not at all happy with the result and quickly realizes that it is pointless to go through all the hustle.
