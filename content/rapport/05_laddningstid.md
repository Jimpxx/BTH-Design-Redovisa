---
---
Laddningstid
=========================

Detta är en rapport av en analys av tre webbplatser, analysen görs för att mäta laddningstiderna för tre stycken sidor för tre webbplatser, så totalt nio sidor ska analyseras och jämföras för att se om något kan förbättras.

Urval
-----------------------

Mina val:

1. [DustinHome](https://www.dustinhome.se/)

2. [Inet](https://www.inet.se/)

3. [NetOnNet](https://www.netonnet.se/)


Jag valde att analysera samma webbplatser jag analyserade färger på, dels för att jag spenderar relativt mycket tid på dem, men också för att jag tyckte det passade in att göra en laddningstidsanalys på dem då de är väldigt lika och de hör till samma kategori.

Till varje webbplats väljs tre sidor ut för analys. Jag har valt att ha tre liknande sidor för varje webbplats för att jämförelsen ska bli relativt rättvis. Jag har därför valt hemsidan för alla 3 webbplatser samt sidan kundservice för DustinHome och Inet. Netonnet hade ingen sida som heter Kundservice, jag valde därför Netonnets sida "Kontakta oss". Som den tredje sidan valde jag sidan "Datorkomponenter" hos alla tre webbplatser.


Metod
-----------------------

För att utföra analysen krävs ett verktyg för att mäta laddningstiderna för sidorna. Detta görs med Google Pagespeed och webbläsarens inbyggda verktyg Devtools (Fliken Network). Google Spreadsheets kommer också användas för att dokumentera resultaten av analysen.


Resultat
-----------------------

Denna sektion består av en analys av tre sidor hos tre webbplatser, nio sidor totalt som analyseras genom Google Pagespeed och genom webbläsarens verktyg - Devtools.

[Länk till rådata](https://docs.google.com/spreadsheets/d/1yHzdhWkl3Afx9fxeTmDrDXIf01Vc9XshVKa3RBqvQ8w/edit?usp=sharing)

#### DustinHome ####

Snapshot av DustinHome.

![Snapshot of DustinHome](./image/dustinhome.PNG?w=400)
<!-- [FIGURE src=image/dustinhome.png?w=400] -->

<!-- 

 -->

Sidor:

[Hem](https://www.dustinhome.se/)

[Kundservice](https://www.dustinhome.se/service)

[Datorkomponenter](https://www.dustinhome.se/group/hardvara/datorkomponenter/)


Förbättringar:

DustinHome kan förbättra sin sida genom att arbeta mer med sina bilder. Enligt Google Pagespeed så kan de byta sina bilder till nyare format. De kan även "koda" sina bilder mer effeltivt och ta bort eller oanvänd CSS från sin sida. De kan också förbättra sin sida genom att aktivera textkompression på sin webbplats. De fick lägst poäng i Google Pagespeeds test. 

Enligt min analys genom Devtools gör det ett mindre bra jobb med sin sida. Deras webbplats verkar vara den långsamaste av de tre när man jämför antal resurser och storlek som laddas på webbplatsen.



#### Inet ####

Snapshot av Inet.

![Snapshot of Inet](./image/inet.PNG?w=400)
<!-- [FIGURE src=image/inet.png?w=400] -->

<!--

-->

[Hem](https://www.inet.se/)

[Kundservice](https://www.inet.se/info/175/kundservice)

[Datorkomponenter](https://www.inet.se/kategori/31/datorkomponenter)


Förbättringar:

Inet kan förbättra sin sida genom att även de arbeta mer med sina bilder. Enligt Google Pagespeed så kan de byta sina bilder till nyare format. De kan även jobba mer med att göra om storlekarna på bilderna till "bättre" storlekar. De kan också förbättra sin sida genom att minifiera sin Javascriptkod. De fick högst poäng i Google Pagespeeds test. Enligt min analys genom Devtools gör det ett bra jobb med sin sida, deras webbplats verkar vara snabbast genom alla sidor relaterat till den storlek som laddats in om man jämför de tre webbplatserna.


#### NetOnNet ####

Snapshot av NetOnNet.

![Snapshot of Netonnet](./image/netonnet.PNG?w=400)

<!--

-->

[Hem](https://www.netonnet.se/)

[Kontakta Oss](https://support.netonnet.se/hc/sv/articles/360001160045-Kontakta-oss)

[Datorkomponenter](https://www.netonnet.se/art/datorkomponenter)


Förbättringar:

Netonnet kan förbättra sin sida genom att också de arbeta mer med sina bilder. Enligt Google Pagespeed så kan de byta sina bilder till nyare format. De kan även jobba mer med att göra om storlekarna på bilderna till "bättre" storlekar. Enligt min analys genom Devtools gör det ett bra jobb med sin sida. De kommer på andra plats i min analys.



Analys
-----------------------

Resultatet av Googles Pagespeed verkar enligt mig bero helt på bilderna på sidan. De flesta optimeringstips som visades på sidan verkade relatera till bilder. Alla tre webbplatserna behöver jobba mer med sina sidor enligt Google Pagespeed. Enligt min analys så var Inet snabbare bland de tre och DustinHome var den långsammaste när man jämför antalet resurser och storleken som laddas in till webbplatsen.

Personligen tycker jag inte någon av de tre är direkt långsamma webbplatser. Jag tror att jag skulle börja reagera vid 3-5 sekunders laddningstid. Då skulle jag märka av det och störa mig på det. vid 5-10 sekunders laddningstid skulle jag aktivt välja att undvika webbplatsen och även stänga ner sidan om jag var inne på den. Jag skulle säga att under 3 sekunder räknar jag det som en "snabb" sida och över det räknas de som långsamma enligt mig. Mitt urval av webbplatser klarar alltså min gräns för att räknas som snabba webbplatser.



Referenser
-----------------------

Mina referenser:

* [Google Pagespeed](https://developers.google.com/speed/pagespeed/insights/)


Övrigt
-----------------------

En observation jag gjorde:

När jag gjorde min analys på Netonnet med Devtools upptäckte jag att sidan laddade in allt som den skulle och sedan ca. 10 sekunder senare laddade den in något mer. Efter lite undersökning upptäckte jag att Netonnet har ett bildspel och den byter bild med ca. 10 sekunders mellanrum och det är därför sidan laddar in mer efter en stund. Trodde först att det var något som tog lång tid att laddas in eller något liknande.

Jag gjorde undersökningen själv, Jimmy Andersson
