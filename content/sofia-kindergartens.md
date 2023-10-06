---
title: Посещаемост в детските ясли и градини в София през учебната 2021/2022 година
draft: false
categories: [ "education" ]
color: "orange"
type: "blog"
---
<body onload="initViz();">
    <div id="vizContainer" style="width:100%; min-width: 600px; height:800px;" class="mx-auto"></div>
    <div class="mt-5">
        <p>
            Повече информация за визуализацията може да прочетете в <a href="https://data-for-good.bg/posts/2022-03-15-sofia-kindergartens-2021-2022/">публикацията по темата</a>.
        </p>
        <p>
            Всички налични данни обобщени и използвани в приложението са достъпни в машинночетим формат като
            <a href="https://docs.google.com/spreadsheets/d/1dKUV7q9GlrIgsWbw6DNhkjjFFjY-aNnDOtEcM7ZC4Gk/export?format=xlsx">XLSX</a>
        </p>
        <p>
            Суровите данни предоставени от Столична община в отговор на запитвания по ЗДОИ са достъпни <a href="https://drive.google.com/drive/folders/1jQDSzg3rYrBJ6kXaqHGMOQdr76l0yRC7?usp=sharing">тук</a>.
        </p>
    </div>
    <script type="text/javascript" src="https://public.tableau.com/javascripts/api/tableau-2.min.js"></script>
    <script type="text/javascript">
        function initViz() {
            var containerDiv = document.getElementById("vizContainer"),
                url = "https://public.tableau.com/views/SofiaKindergartens20212022/SofiaKindergartens",
                options = {
                    hideTabs: true,
                    onFirstInteractive: function () {
                        console.log("Run this code when the viz has finished loading.");
                    }
                };
            var viz = new tableau.Viz(containerDiv, url, options);
            // Create a viz object and embed it in the container div.
        }
    </script>
</body>