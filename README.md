# browser-technologies-herkansing

Het vak Browser Technologies draait volledig om het toegankelijk maken van het web op browser niveau. Dit houdt in dat als je de website bekijkt als je geen JavaScript of CSS in je browser hebt, de website alsnog werkt.

## De user case
De user case die ik gekozen heb voor dit vak is:

"Ik wil boodschappen-om-tostis-te-maken in mijn boodschappenlijstje kunnen gooien."

**Uitdagingen**
 - Server-side scripting
   - Ik wilde server-side toepassen, zodat de website ook gebruikt kan worden zonder JavaScript. Dit vind ik uitdagend, omdat ik naast project Tech nooit gewerkt had met het server side afhandelen van formulieren. Hier moet ik weer inkomen en veel gaan Googlen.
 - Vormgeving
   - Vormgeving is iets waar ik altijd moeite mee heb gehad. Ik wil dat het lijstje er goed uitziet. Het ontwerp moet nu ook zo gecodeerd worden dat het op elke browser perfect werkt.
 - Het ontwerpen van een unieke ervaring
   - Als het lijstje staat en werkt naar behoren wil ik nog een unieke ervaring toevoegen. Dit zal iets zijn waardoor het gebruik van het lijstje leuker maakt om te gebruiken.
   
## Mijn process
### HTML
De HTML moet goed worden opgemaakt en zal gebruikt worden als de basis. Daarom moet het semantisch en logisch worden opgebouwd. Naast basis HTML heb ik in deze laag ook gewerkt aan het samenstellen van de data (de producten van het lijstje), het maken van de .ejs templates en werken aan de server-side scripting. Na een paar tutorials gekeken te hebben over Node JS en na het overleggen op werk of de uitwerking in mijn hoofd de meest semantische manier was, kon ik aan de slag.


### CSS
Na inspiratie opgezocht te hebben online heb ik een ontwerp designed. Dit is in de style van minimalisme. Het lijstje is duidelijk zichtbaar en spreekt voor zichzelf. Met CSS heb ik me gefocused dat het accessible is voor iedereen, dus ook voor mensen met een handicap.
Voor de kleuren en hover/focus states heb ik gebruik gemaakt van [funkify](https://www.funkify.org/) om een goeie kleur contrast te bepalen. De tab route is logisch opgezet, dus de gebruiker kan er gemakkelijk door heen gaan. Voor de rest heb ik CSS code gebruikt dat op oudere browsers ook support wordt. hier voor heb ik zowel gebruik gemaakt van [caniuse](https://caniuse.com/) als [browserstack](https://www.browserstack.com/) om te testen of het lijstje het overal optimaal doet. 


### JavaScript
