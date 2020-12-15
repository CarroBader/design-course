---
Title: Load Time
Description: Load Time analyse page
Template: index
---

<div class="kmom-div list-box content-desktop">
    <ul>
        <li><a href="01_colors" class="report-link" aria-label="colors">Colors</a></li>
        <li><a href="02_load" class="report-link active" aria-label="laod time">Load Time</a></li>
        <li><a href="03_design_principles" class="report-link" aria-label="design principal">Design Principal</a></li>
    </ul>
</div>

<h1>Load time</h1>

<p>Nedan kommer det att finnas en analys av tre stycken företags hemsidors prestanda. De kommer att disukteras för sig men även jämföras med varandra.
</p>

<h2 class="analysis-h2">Urval</h2>

I denna analys har det valt att titta på hemsidor från tre hemsidor från liknande branscher, de valta hemsidorna är formula1.com, laliga.com och nba.com. Jag valde dessa då de kan tänkas ha likande trafik och även samma mål i sina sidor d.v.s. informera fans om kommande event men även dela bilder och videos från gamla event.

<h2 class="analysis-h2">Metod</h2>

<p>Efter hemsidan var vald så togs en skärmbild, med hjälp av Macs inbyggda verktyg. Därefter så har Google Pagespeed används på alla hemsidor, de har sedan undersöks deras nätverks data i Chrome Devtools. Sifforna från dessa undersökningar går att hitta i ett Google sheet.

</p>

<h2 class="analysis-h2">Resultat</h2>

<div class="webpage-div">
    <h3 class="analysis-h3">Formula One<h3>
    <img src="{{ base_url }}../../../assets/img/f1.png" alt="f1">
    <hr>
    <a href="https://docs.google.com/spreadsheets/d/1rC1J31MOPyrSSSpEjfvFdh-JON--ivfVIEHcsazMNqI/edit?usp=sharing" style="color:#152238" target="_blank" aria-label="google data">Google sheet data</a>
    <p>Förbättring</p>
    <p>Formula One klarade sig hyfsat bra i Google Pagespeed testet för desktop men var långt ifrån i mobilmätningen. Laddningstiden var även lite över 3s på alla mätningarna, så finna lite att jobba med där med.</p>
</div>

<div class="webpage-div">
    <h3 class="analysis-h3">La Liga<h3>
    <img src="{{ base_url }}../../../assets/img/laliga.png" alt="ll">
    <hr>
    <a href="https://docs.google.com/spreadsheets/d/1rC1J31MOPyrSSSpEjfvFdh-JON--ivfVIEHcsazMNqI/edit?usp=sharing" style="color:#152238" target="_blank" aria-label="google data">Google sheet data</a>
    <p>Förbättring</p>
    <p>La Liga klarade sig vädligt dåligt i Google Pagespeed testet för både desktop och mobil så där finns mycket att jobba med.</p>
</div>

<div class="webpage-div">
    <h3 class="analysis-h3">NBA<h3>
    <img src="{{ base_url }}../../../assets/img/nba.png" alt="nba">
    <hr>
    <a href="https://docs.google.com/spreadsheets/d/1rC1J31MOPyrSSSpEjfvFdh-JON--ivfVIEHcsazMNqI/edit?usp=sharing" style="color:#152238" target="_blank" aria-label="google data">Google sheet data</a>
    <p>Förbättring</p>
    <p>NBA klarade sig hyfsat bra i Google Pagespeed testet för desktop men var väldigt långt ifrån i mobilmätningen.</p>
</div>


<h2 class="analysis-h2">Analys</h2>

<p>
Alla tre hemsidorna hade dåliga värden i just mobil hemsidan så här är några sätt att förbättra det.
</p>
<ul>
<li>* Använda komprimerade bilder</li>
<li>* Minimera koden, använd inte all kod från hemsidan om du inte behöver</li>
<li>* Se över javascripten och använda språkets uppdateringar</li>
</ul>
<p>
Formula One klarade Google Pagespeed bäst i både kategorierna, dock var NBA:s hemsida hack i häl gällande Desktop. De två nyss nämda var de två som inte hamnade i den röda sektionen i desktop medan alla tre hamnade där i mobilsidan. Vilket är något all hemsidorna borde jobba med då surfandet har börjat och kommer att fortsätta att gå över till mobilen. Dessa hemsidorna har mycket att jobba på i den avdelning. Även i desktop mode, särskilt La Liga som hamnade i den röda sektionen. NBA had högst överlag lägst laddningstid men också minst resurser att läsa in. Formula One hade snäppet fler resurser and La Liga men deras laddningstider var olika, Formula One höll en konsekvent nivå i sina laddningar medan La Liga gjorde större hopp meddlan tiderna. NBA är den bästa sidan efter Devtools nalysen men som sagt har de även minimerat sitt innehåll, utifrån Google Pagespeed så är Formula One bäst vilket jag kan hålla med om. Så placerar de på samma plats med La Liga är den sämsta av dem.
</p>
<ul>
<li>* Formula One</li>
<li>* NBA</li>
<li>* La Liga</li>
</ul>
<p>
Skulle säga att okej lddningstid är mellan 2-3 sekunder, vilket de tre sidorna höll sig inom. La Liga hade en omladdning som var upp på 4 sekunder vilket är i det högsta laget. Man märker snabbt när det tar lite extra tid då vi är så vana att allt ska gå snabbt nu. Folk förväntar sig mer av företagen och är svårare att behaga.
</p>

<h2 class="analysis-h2">Referenser</h2>

<p>Google Pagespeed</p>
<p>Chrome Devtools</p>
<p class="analysis-link"><a href="https://www.formula1.com" aria-label="f1">F1 - hemsida</a></p>
<p class="analysis-link"><a href="https://www.laliga.com" aria-label="la liga">La Liga - hemsida</a></p>
<p class="analysis-link"><a href="https://es.nba.com" aria-label="nba">NBA -  hemsida</a></p>

<h2 class="analysis-h2">Övrigt</h2>

<p>Denna analysen är skriven av Caroline Bader.</p>
