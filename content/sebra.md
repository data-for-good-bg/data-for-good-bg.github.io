---
title: "СЕБРА - Плащания по институции"
draft: false
categories: [ "democracy" ]
color: "cyan"
type: "blog"
---
<body onload="initViz();">
    <div id="vizContainer" style="width:100%; min-width: 600px; height:800px;" class="mx-auto"></div>
    <div class="mt-5">
        <p>
            Всички налични данни от СЕБРА използвани в приложението са достъпни в машинночетим формат като
            <a href="https://docs.google.com/spreadsheets/d/1VoB4dIH2Y2x2O-eH0ivNmBUYCcT-1NR6T5h8eWkE33Y/export?format=xlsx" target="_blank">XLSX</a>
            и <a href="https://docs.google.com/spreadsheets/d/1VoB4dIH2Y2x2O-eH0ivNmBUYCcT-1NR6T5h8eWkE33Y/gviz/tq?tqx=out:csv&gid=1639699984" target="_blank">CSV</a>.
        </p>
        <p>
            Кодът на програмите за чистене и форматиране на входните данни са достъпни в <a href="https://github.com/data-for-good-bg/sebra-scrape">github</a>.
        </p>
        <p>
            Повече информация за визуализацията може да прочетете в нашия <a href="https://data-for-good.bg/blog/sebra-visualization-bg">блог</a>.
        </p>
    </div>
    <script type="text/javascript" src="https://public.tableau.com/javascripts/api/tableau-2.min.js"></script>
    <script type="text/javascript">
        function initViz() {
            var containerDiv = document.getElementById("vizContainer"),
                url = "https://public.tableau.com/views/SEBRAdashboard/Story",
                options = {
                    hideTabs: true,
                    onFirstInteractive: function () {
                        console.log("Run this code when the viz has finished loading.");
                    }
                };
            var viz = new tableau.Viz(containerDiv, url, options);
            // Create a viz object and embed it in the container div.
        }</script>
</body>
