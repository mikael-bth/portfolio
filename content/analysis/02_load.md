---
Title: Load
Description: Load analysis page.
Template: analysis
---

Laddningstid och användbarhet analys
====================================

<div class="links">
<a href="01_colors">Colors</a>
<a href="02_load" class="active">Load</a>
<a href="03_design_principles">Design principles</a>
</div>

<div class="text">
<p>
I den här rapporten ska jag analysera webbsidors laddningstid och hur vad de har gjort för att förbättra laddningstiden och vad de
kan jag för att förbättra den.
</p>

<h2>Urval</h2>

<p>
För mitt urval så valde jag att analysera webbsidorna: w3schools, twitter och amazon. Detta är samma urval som för min förra analys på
färgval, jag valde att fortsätta med dessa sidor eftersom det representera stora delar av webbplatser på internet. Jag valde också att
fortsätta med dessa webbsidor eftersom jag tycker det hade varit intressant att gå in djupare och analysera specifika sidor och kunna
bygga upp på den kunskapen istället för att hoppa runt till flera sidor då man lätt kan tappa bort sig.
</p>

<ul>
    <li><a href="https://www.w3schools.com/">w3schools</a></li>
    <li><a href="https://twitter.com/home?lang=sv">Twitter</a></li>
    <li><a href="https://www.amazon.com/">Amazon</a></li>
</ul>

<h2>Metod</h2>
<p>
För att analysera webbsidornas laddningstid så kommer jag använda verktygen PageSpeed Insights för att se vilket betyg den får för prestandan
på sidan, Google Chromes network verktyg för att se laddningstiden, hur många resurer det finns på sidan och sidans totatala storlek. Jag kommer
också använda Google Kalkylark för att spara ner informationen på ett smidigt sätt. 
</p>

<h2>Rå data</h2>
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTvepPdYkHxXOwTxYHDDUhNIf6CYHL9ZbwxhpAJkpnjdXv2EkzTLy7yNuiygqfEVzmvwTtrF6Ssxvz-/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

<h2>Resultat</h2>
<div class="webpage">
    <img src="../image/w3schools.png?save-as=jpg">
</div>
<p>
W3schools<br>
W3schools sidor som mättes:
<ul>
    <li><a href="https://www.w3schools.com/">W3schools Startsida</a></li>
    <li><a href="https://www.w3schools.com/css/default.asp">W3schools CSS</a></li>
    <li><a href="https://www.w3schools.com/js/default.asp">W3schools JS</a></li>
</ul>
<div class="speed-grade">
<img src="https://i.gyazo.com/5756f9531559e77d30ed82c58b456dee.png" class="page-grade">
<img src="https://i.gyazo.com/8e062f7696141580569c02086a35b7b3.png" class="page-grade">
<img src="https://i.gyazo.com/0625f90242d9de57f2f120640de81b8a.png" class="page-grade">
<img src="https://i.gyazo.com/c0b9ca2f43aaa1141e1357c322f06bd7.png" class="page-grade">
<img src="https://i.gyazo.com/6763ea5258aa71cf8f141f183bb1abdf.png" class="page-grade">
<img src="https://i.gyazo.com/2f289a9f4bf3ee3bcdcd44ffa0d19931.png" class="page-grade">
</div>
W3schools dator sidor fick ett strålande betyg på 100 på de tre sidor som testades medans mobila verisionen va lite sämre där de hade ett medelvärde
på 90 men även ett ganska bra betyg.<br>
W3schools startsida hade en laddningstid på 532ms medans CSS och JS låg på en lite lägre ~350ms, startsidan hade också 20st resurser som hämtades in
medans CSS och JS låg runt 13 - 14st. Sidans totala storlek låg runt 809kB medans CSS och JS sidorna låg runt 330kB.<br>
För att förbättra sidan så kan göra så alla bildelement har en bestämnd storlek och höjd, minska på JavaScript som inte används och använda nyare
bildformat med bättre komprimering.
</p>
<div class="webpage">
    <img src="../image/twitter.png?save-as=jpg">
</div>
Twitter<br>
Twitter sidor som mättes:
<ul>
    <li><a href="https://twitter.com/login?lang=sv">Twitter Login</a></li>
    <li><a href="https://twitter.com/deanjnorris">Twitter Profil Sida</a></li>
    <li><a href="https://help.twitter.com/en">Twitter Help</a></li>
</ul>
<div class="speed-grade">
<img src="https://i.gyazo.com/0af2216e87dfe98c2ea2891c725d65d9.png" class="page-grade">
<img src="https://i.gyazo.com/d3858df32a423ecd17f9d796ca1b1ae5.png" class="page-grade">
<img src="https://i.gyazo.com/90e0caf2a6316c5972e01242c8f7958b.png" class="page-grade">
<img src="https://i.gyazo.com/c69a540504376bf19b7af9d91284b8ca.png" class="page-grade">
<img src="https://i.gyazo.com/d4b69cde40c2c5b1885ef4480eff83b1.png" class="page-grade">
<img src="https://i.gyazo.com/06839bea9acf323bfd40be381a8773ae.png" class="page-grade">
</div>
<p>
Twitters mobila sidor fick ett ganska dåligt betyg där login och profil sidan låg runt 60 men twitters help sida gick så lågt som 24. Twitters dator
sidor hade dock ett bättre betyg där login sidan fick 90 och profil och help sidan låg runt 75.<br>
Twitters login och profil sida hade en laddningstid på ungefär 715ms medans twitters help sida gick så högt som 1.78s. Login och help sidan hade
runt 45 resurser medans profil hade 128st. Storleken på login, profil och help sidorna var respektive 5.8MB, 7.4MB och 4.4MB.<br>
För att förbättra sidan kan twitter minska på javascript som används på sidan, minska storleken på javascript resurserna som skicka och minska på
nätverksbelastningen på sidan.
<div class="webpage">
    <img src="../image/amazon.png?save-as=jpg">
</div>
Amazon<br>
Amazon sidor som mättes:
<ul>
    <li><a href="https://www.amazon.com/">Amazon Startsida</a></li>
    <li><a href="https://www.amazon.com/gp/help/customer/display.html?nodeId=508510&ref_=nav_cs_customerservice_2bf4fe8c5ec54e6bae2d1c24043f012b">Amazon Customer Service</a></li>
    <li><a href="https://www.amazon.com/b/?_encoding=UTF8&ld=AZUSSOA-sell&node=12766669011&ref_=nav_cs_sell_9321d964d1ab428b8d83e204c043fc01">Amazon Seller</a></li>
</ul>
<div class="speed-grade">
<img src="https://i.gyazo.com/8416a1c003f1c8b11375453f7857261c.png" class="page-grade">
<img src="https://i.gyazo.com/a0b0e7f41dfc1c18fca2bf2b262a20b6.png" class="page-grade">
<img src="https://i.gyazo.com/08ac9a09b35025f893f5fcb97ae1c2bb.png" class="page-grade">
<img src="https://i.gyazo.com/adc58d64519231e608ac409200de35ac.png" class="page-grade">
<img src="https://i.gyazo.com/d1443ba53b8151c5e2e3d8bb89be5d58.png" class="page-grade">
<img src="https://i.gyazo.com/dadab57a400f2ad9da66ea677d8ab928.png" class="page-grade">
</div>
<p>
Amazon mobila sidor för startsidan, customer service och seller fick respektive betyg 60, 71 och 56 vilket inte var lika dåligt som twitter men fortfarande
inte jätte bra. Det gick dock bättre för amazons dator sidor där startsida och customer service sidan fick runt 94 och seller fick 85.<br>
Amazons startsida och customer service hade en laddningstid på ~1s medans deras seller sida hade en laddningstid på 1.77s. Startsidan hade 185 resurser,
medans customer service och seller låg på respektive 69 och 59st. Storleken på startsidan och seller sidorna låg runt 3.1MB medans customer service låg
på 1.4MB.<br>
För att förbättra sidan kan amazon skicka bilder i modernare bildformat med bättre komprimering, ta bort resurser som blockerar rendering och göra så att
text är synlig medans fonter laddas in.
</p>
<h2>Analys</h2>
<p>
I resultat delen försökte jag ta upp mer unika delar webbsidorna kunde förbättra så nu tänkte jag gå igenom förbättringar som var vanliga för alla webbsidor.
En an det vanligaste förbättrningarna webbsidorna kunde göra var att använde ett modernare bildformat, nyare bildformat har oftast bättre komprimering och gör
så att bilderna inte tar lika mycket minne och gör därför att de går snabbare att läsa in. Liknande så kunde alla webbsidor gynna av att sätta en bestämd höjd
och bredd för bilderna vilket minskar risken att element förskjuts. Det fanns också många förbättringar inom Javascript för alla sidorna där de kunde: minska
på js som används på sidan, undvika att ha js som inte anväds på sidan och minska storleken på js resurserna på sidan, detta hjälper med laddningstiden för
sidan och minskar på nätverksbelastningen.
</p>
<h2>Bästa Resultatet</h2>
<p>
W3schools var den solklara vinnare i dator webbsidor där alla 3 w3schools sidor jag testade fick 100. Mobila sidorna var lite jämnare men w3schools kom ändå
ut som vinnaren men där de tre sidorna jag testade rundas ut runt 90. Andra platsen för dator webbsidor kom Amazon med ett medelvärde på 91 och trea plats för
dator webbsidor kom twitter med ett medelvärde 80. Tvåa plats för mobila webbsidor blev det Amazon igen med där de tre sidorna jag testa låg runt 62 och 
då blir då twitter trea igen med ett medelbetyg på 49. Sidan med bäst resultat för både mobil och dator blir w3schools och sidan med sämst resultat för mobil
och dator är då twitter.
</p>
<h2>Min åsikt på laddningstid</h2>
<p>
Jag tycker en webbsida borde ha en laddningstid under 1.5 sekunder, 1.5 sekunder är fortfarande en ganska lång laddningstid för en sida men större sidor är
det mer möjligt att nå, så jag skulle säga för en större sida med mer resurser så skulle jag säga en max laddningstid på 1.5 sekunder och för en mindre sida
så skulle jag säga en max laddningstid på 0.75 sekunder. Nästa alla sidorna jag analyserade klarade detta max snittet, w3school hade en väldigt bra laddningstid
och sida kände väldig "smooth" att ladda in. Twitter och Amazon var lite värre där twitters help sida och amazons seller sida gick över laddningstids snittet
men resten av deras sidor klarades sig ganska bra. Jag tycker dock att Twitter och Amazon sidorna inte alls kändes lika "smooth" att ladda in som w3school men
det är ganska förståligt när man jämför storlekarna på sidorna där w3schools största sida var runt 800kB och Twitter och Amazons största sida var respektive
7.4MB och 3.2MB. 
</p>
<h2>Författare</h2>
<p>
Mikael Menonen
</p>
</div>