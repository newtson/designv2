---
---
Analys laddningstid
=========================

Tre webbplatser har valts ut för att jämföra och analysera deras laddningstid.


URVAL
-----------------------

Utförde google sökningar efter listor med webbplatser som har bedömts av andra att vara innehållstunga, innehålls lätta och bra gjorda responsiva.

Från listan över innehållstunga webbplatser valdes [Aiga](https://www.aiga.org/) ut.
[FIGURE src=image/aiga.png?w=300 caption=""]
Sidorna var: [första sidan](https://www.aiga.org/), [andra sidan](https://www.aiga.org/design) och [tredje sidan](https://www.aiga.org/about/)

Från listan över innehålls lätta webbplatser valdes [Brooklyn Soap Company](https://bklynsoap.com/) ut.
[FIGURE src=image/brooklyn.png?w=300 caption=""]
Sidorna var: [första sidan](https://bklynsoap.com/), [andra sidan](https://bklynsoap.com/inception/) och [tredje sidan](https://bklynsoap.com/shop/kits-gifts)

Från listan över responsiva webbplatser valdes [Farm Africa](https://www.farmafrica.org/) ut.
[FIGURE src=image/farmafrica.png?w=300 caption=""]
Sidorna var: [första sidan](https://www.farmafrica.org/), [andra sidan](https://www.farmafrica.org/what-we-do/what-we-do) och [tredje sidan](https://www.farmafrica.org/latest/news)


METOD
-----------------------

Använde PageSpeed Insights och devtools fliken networks för att testa sidornas laddningstid. Tre mätningar gjordes för varje sida. Den första mätningen gjordes på morgonen, den andra mätningen på eftermiddagen och den tredje mätningen på kvällen. Värdena lades in i [Google Kalkylark](https://docs.google.com/spreadsheets/d/15H_r1rN1rKihJLPlCXROAlFCC5W_Y3baRCfPkf7QSGI/edit#gid=0).  


RESULTAT
-----------------------

Från de tre mätningarna som utfördes på varje sida togs det genomsnittliga värdet ut.  De genomsnittliga värdet för varje sida på en webbplats lades sedan ihop och genomsnittliga värdet togs utav det. Nedan presenteras det resultatet.

##### Aiga:

PageSpeed Insight (desktop): 95<br />
network laddningstid:        7,37 s  
network förfrågningar:       65<br />
network storlek:             5,08 MB

PageSpeed Insight (mobile): 64<br />
network mobil laddningstid: 8,94 s<br />
network mobil förfrågningar: 65<br />
network mobil storlek:       2,99 MB


##### Brooklyn Soap Company:

PageSpeed Insight (desktop): 87<br />
network laddningstid:       14,32 s<br />
network förfrågningar:      121<br />
network storlek:            5,69 MB

PageSpeed Insight (mobile):  18<br />
network mobil laddningstid:  12,17 s<br />
network mobil förfrågningar: 120<br />
network mobil storlek:       5,46 MB


##### Farm Africa:

PageSpeed Insight (desktop): 100<br />
network laddningstid:        8,15 s<br />
network förfrågningar:       66<br />
network storlek:             2,72 MB

PageSpeed Insight (mobile):  60<br />
network mobil laddningstid:  6,07 s<br />
network mobil förfrågningar: 64<br />
network mobil storlek:       2,71 MB


Enligt resultaten för desktop från PageSpeed Insight har Farm Africa och Aiga en snabb laddningstid. Brooklyn Soap Company har en genomsnittlig laddningstid, till gränsen på snabb.
Enligt resultaten för mobil från PageSpeed Insights har Farm Africa och Aiga en genomsnittlig laddningtid medan Brooklyn soap company har en långsam laddningstid.


ANALYS
-----------------------

Då 46% av användare överger en sida om den tar längre tid än tre sekunder att ladda (Ryan, 2016) är en snabb laddningstid viktig att uppnå. I denna undersökning var Farm Africa vinnaren med Aiga som två och Brooklyn Soap Company på tredje plats. Det verkar som Farm Africa har lagt ner tid på sina bilder då de mest tidsbesparande förslag som gavs för denna webbplats var, "Skicka bilder i modernare bildformat" och "Koda bilder effektivt". Eftersom det ännu inte finns stöd i alla webbläsare för modernare bildformat (Google Developers, 2018) så är det förståligt att de inte gjort denna. För Aiga var det förslag som hade mest effekt, med en tidsbesparing som beräknades vara 2,1 sekunder, var "Använd bilder med rätt storlek". En sådan åtgärd borde vara ganska lätt att genomföra och borde därför göras för att minska laddningstiden och därmed minska förlust av besökare. För Brooklyn Soap Company var det också åtgärder för bilder som hamnade i första plats av förbättringsförslagen. I deras fall var det förslaget "Skjut upp inläsning av bilder som inte visas på skärmen". Eftersom de hade den högsta laddningstiden av de tre webbplatserna och deras laddningstid var på över 10 sekunder så behöver de arbeta på att ta ner den på alla områden som de kan. Att skjuta upp inläsningen av bilderna är ett bra förslag och borde kunna uppnås ganska enkelt.

Denna undersökning har fokuserat på bilder och har därmed, och pga. tidsbrist, inte gått in djupare i anledningen för Brooklyn Soap Company långsamma laddningstid. T.ex. så kunde förfrågningarna studeras närmare då Brooklyn Soap Company har många fler förfrågningar än de andra två webbplatserna. Vad som kan sägas är att Brooklyn Soap Companys webbplats laddningstid skulle kunna ha förbättras med över 2 sekunder, enligt beräkning från pagespeed insight, ifall "Skjut upp inläsning av bilder som inte visas på skärmen" utfördes. Vilket visar att bild hantering kan ha en stor effekt på laddningstiden. Brooklyn Soap Company har väldigt mycket sämre resultat i mobil än de har i desktop, det kan bero på att de kanske inte har gjort mobile first utan har först gjort deras webbplats i desktop och sedan inte anpassat till mobil utan mest låtit den vara. 

Personligen var laddningstiderna för Aiga och Farm Africa okej för mig. Jag blev inte frustrerad och ville klicka vidare. Det fick däremot Brooklyn Soap Company mig att vilja göra. Medan jag inte upplevde det som en katastrofal laddningstid så kände jag fingrarna vilja klicka tillbaks till google istället för att vänta. Så jag antar att mitt gränsvärde är ungefär 6, 7 sekunder.

Om användare börjar överge en sida efter tre sekunder så har alla dessa webbplatser som undersöktes i denna studie förlorat besökare, vissa mer än andra. Att förlora besökare är att förlora pengar, vilket ingen vill göra. Eftersom bilder utgör mer än 60% av bytes vid nedladdning av en webbplats (LePage 2018) så är det viktigt att man tänker på deras storlek, format, inläsning osv. för att hålla ner laddningstiden. Alla tre webbplatserna kan förbättra sina tider genom att fokusera på sina bilder.


REFERENSER
-----------------------

Google Developers (2018). "Serve Images in Next-Gen Formats". https://developers.google.com/web/tools/lighthouse/audits/webp. Accessed on 2018-12-07.

LePage, P (2018). "Images". Web. https://developers.google.com/web/fundamentals/design-and-ux/responsive/images. Accessed on 2018-12-05.

Ryan, D (2016)."Websites are slowing down because of complex design trends". Developer. https://www.developer-tech.com/news/2016/jun/02/websites-are-slowing-down-because-complex-design-choices/. Accessed on 2018-12-08.


ÖVRIGT
-----------------------

Detta arbete är utfört av Marie Eriksson.
