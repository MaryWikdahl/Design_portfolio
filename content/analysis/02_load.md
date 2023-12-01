
Analys av tre högskolers prestandard
=======================

Jag har valt att analysera tre högskolors webbplatser och mäta hur snabbt de laddas samt försöka se om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet. 

Urval
-----------------------
Jag har valt att analysera hemsidorna för tre olika högskolor. De jag valde var Blekinge Tekniska Högskola (Bth), Linköpings Universitet (Liu) och Ec utbildning (Ec). Jag valde dessa då jag vid något tillfälle studerat vid dem.
Att analysera dessa webbplatser är intressant, särskilt med tanke på det stora antalet besökare de har. Det är avgörande att säkerställa snabba laddningstider för en smidig användarupplevelse.


Metod
-----------------------
Jag har valt att använda mig av PageSpeed Insights för att mäta prestandard på dessa webbplatser. Jag kommer att sammanställa de olika resultat i en excel fil. Jag kommer först titta på prestandarn för mobil- sedan dator-användning. Jag har även för varje sida mätt med devtools flik networks, sidornas laddningstider tillsammans med dess anatal resurser som laddas samt sidornas totala storlek.

Resultat
-----------------------
https://www.bth.se/ <br>
![Bth](%assets_url%/img/bth.png) <br>
![Bth-prestanda-mobil](%assets_url%/img/Prestanda-bth.png)
![Bth-prestanda-desktop](%assets_url%/img/prestanda-dator-bth.png)

https://liu.se/

![liu](%assets_url%/img/liu.png)<br>
![liu-prestanda-mobil](%assets_url%/img/Prestanda-liu.png)
![liu-prestanda-desktop](%assets_url%/img/prestanda-dator-liu.png)

https://ecutbildning.se/

![ec](%assets_url%/img/ec.png)<br>
![ec-prestanda-mobil](%assets_url%/img/Prestanda-ec.png)
![ec-prestanda-desktop](%assets_url%/img/prestanda-dator-ec.png)

<div class="embed-container">
    <iframe src="https://1drv.ms/x/s!AjA4LlCl2KYdhB193OGtz3QDtYsd?e=97bUw9" frameborder="0"></iframe>
</div>
    

Det är tydliga skillnader i prestanda mellan de tre webbplatserna, särskilt när vi jämför resultaten mellan mobila och stationära enheter

Mobil Prestanda:

Liu.se framstår som den överlägset snabbaste webbplatsen när vi tittar på resultaten från mobila enheter. Den har korta laddningstider och låga blockeringstider. Resultaten för First Contentful Paint, som mäter den första sidans innehålls synlighet, visar att Liu var snabbast med 1,5 sekunder medans Bth hade sämst resultat med 3,3 sekunder.

Total Blocking Time, som mäter den totala tiden användaren spenderar i väntan på att kunna interagera, visar att Liu.se återigen har bäst resultat med 50ms jämfört med Ec som hade sämst resultat med 1170 ms. 

Largest Contentful Paint, som mäter tiden det tar för den största synliga sidans innehåll att laddas, visade dock Ec bäst resultat med 3,4 sekunder. Här hade Liu sämst resultat med 5,8 sekunder. 

Speed Index, som mäter hur snabbt innehållet visas under laddningen. Var återigen Liu i framkant med 2,9 sekunder jämfört med Bths resultast på 5 sekunder.

Cumulative Layout Shift, som mäter sidans stabilitet, lågt värde indikerar få layoutförändringar, hade Ec bäst reultat med 0.022 och här hade liu sämst med 0,37.

Stationär Prestanda:

Resultaten för stationära enheter visar en annan bild. Liu.se presterar fortfarande starkt, men skillnaderna mellan webbplatserna är mindre uttalade.

I First Contentful Paint, är Liu snabbast med 0,4 sekunder, medan Bth har förbättrats till 0,8 sekunder, och Ec har 0,9 sekunder.

Total Blocking Time, visar att Liu fortsätter att vara överlägsen med endast 10 ms. Bth har förbättrats, men Ec har ökat till 120 ms jämfört med de tidigare 50 ms.

Largest Contentful Paint, visar att Ec presterar bäst med 1,2 sekunder. Liu har förbättrats från 5,3 sekunder till 1,4 sekunder, och Bth har förblivit relativt konstant med 1,4 sekunder.

Speed Index, är samtliga resultat bättre Liu visar dock bäst med 0,7 sekunder tätt följt med Bth 1 sekund och Ec på 1,1 sekund. 

Cumulative Layout Shift har även det förbättrats på stationära enheter. Bth har bäst resultat med 0 medans Liu har sämst med 0.567.

När jag kollar på sidornas laddningstid tillsammans med dess antal resurser som laddas samt sidornas totala storlek. Så får jag först fram att Bth har en laddningstid på ca 7500ms, den har 79 resurser och är 1,7mb stor. Liu har en laddningstid på ca 900ms har 20 resurser och är 707kb stor. Ec har en laddningstid på ca 2100ms,  de har 59 resurser och är 1.1mb stor

Analys
-----------------------
Skillnaderna i prestanda mellan Bth.se, Liu.se och Ecutbildning.se är tydliga när vi granskar resultaten från både mobila och stationära enheter. På mobila enheter framträder Liu.se som den snabbaste webbplatsen med korta laddningstider och låga blockeringstider. Resultaten från First Contentful Paint och Total Blocking Time visar Liu.se som överlägsen, medan Ecutbildning.se presterar starkt i Largest Contentful Paint. Stationärt sett förbättras Liu.se ytterligare, men skillnaderna mellan webbplatserna minskar. Sammantaget visar dessa resultat på varje webbplats styrkor och förbättringsområden, med Liu.se som den övergripande prestandaledaren och Ecutbildning.se som har vissa starka resultat trots vissa utmaningar.

Även när man kollar på laddningstid så har liu bäst resultat med bäst prestanda och snabbare laddningstider, samt färre resurser och mindre data. Bth.se har längre laddningstid och använder fler resurser samt mer data, vilket indikerar möjligheter till optimering medans Ecutbildning.se ligger någonstans mellan de andra två i prestanda.

Bth skulle kunna förbättra prestandan genom att optimera bildstorlekar och implementera tekniker som minimerar skript och stilar för att minska laddningstid, resursanvändning och total sidstorlek.

Sammanfattningsvis visar dessa detaljerade resultat på tydliga styrkor och förbättringsområden för varje webbplats. Liu.se utmärker sig genom konsekvent snabba laddningstider och låga blockeringstider de blir därför vinnarna, medan Ecutbildning.se presterar starkt i snabba Largest Contentful Paint-tider och får därför en andra plats. På tredje plats kommer Bth.se. De kan gynnas av att optimera vissa aspekter av prestanda för att förbättra övergripande användarupplevelse på både mobila och stationära enheter.
Jag anser att en laddningstid på upp till 2 sekunder kan anses som snabbt, medan över 4 sekunder uppfattas som långsamt. Baserat på detta gränsvärde presterar Liu.se mycket bra med laddningstider under 2 sekunder, vilket ger en snabb och responsiv användarupplevelse. Ecutbildning.se visar varierande resultat, medan Bth.se, även om förbättrad, ligger nära gränsen för vad som betraktas som snabbt och kan dra nytta av ytterligare optimeringar för att öka hastigheten och förbättra användarupplevelsen.


Referenser
-----------------------
Moz. (s.f.). Page Speed. Hämtad från https://moz.com/learn/seo/page-speed
Google. (2023, november 30). Using page speed in mobile search ranking. Hämtad från https://developers.google.com/search/blog/2018/01/using-page-speed-in-mobile-search

Övrigt
-----------------------

Mary Wikdahl 