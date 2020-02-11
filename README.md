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
De HTML moet goed worden opgemaakt en zal gebruikt worden als de basis. Daarom moet het semantisch en logisch worden opgebouwd. Ik werk met `<select>` en `<options>` voor de opmaak van het lijstje. Naast basis HTML heb ik in deze laag ook gewerkt aan het samenstellen van de data (de producten van het lijstje), het maken van de .ejs templates en werken aan de server-side scripting. Na een paar tutorials gekeken te hebben over Node JS en na het overleggen op werk of de uitwerking in mijn hoofd de meest semantische manier was, kon ik aan de slag. 


### CSS
Na inspiratie opgezocht te hebben online heb ik een ontwerp designed. Dit is in de style van minimalisme. Het lijstje is duidelijk zichtbaar en spreekt voor zichzelf. Met CSS heb ik me gefocused dat het accessible is voor iedereen, dus ook voor mensen met een handicap.
Voor de kleuren en hover/focus states heb ik gebruik gemaakt van [funkify](https://www.funkify.org/) om een goeie kleur contrast te bepalen. De tab route is logisch opgezet, dus de gebruiker kan er gemakkelijk door heen gaan. Voor de rest heb ik CSS code gebruikt dat op oudere browsers ook support wordt. hier voor heb ik zowel gebruik gemaakt van [caniuse](https://caniuse.com/) als [browserstack](https://www.browserstack.com/) om te testen of het lijstje het overal optimaal doet. 


### JavaScript
Voor de extra ervaring heb ik besloten om het versturen van het lijstje op dezelfde pagina te houden als waar je het samenstelt. Dit scheelt weer een opnieuw inladen van een nieuwe pagina. Ook heb ik een extra animatie toegevoegd. Dit zorgt nu dat het moment dat je het formulier verstuurt, het inklapt en dat een bonnetje (inclusief scherpe randjes) met daarop je ingrediënten naar beneden komt. Ik was geïnspireerd door de Albert Heijn voor dit.

### Support en feature detection
- CSS variable
  - 93.15%
    - De reden waarom ik met CSS variable werk is, omdat ik up-to-date wil blijven met de nieuwste CSS technieken. Dit probleem kan   verholpen worden door geen variable te gebruiken.
    
- QuerySelector
  - 97.6 %
    - Om ervoor te zorgen dat 100% van mijn gebruikers de site kan gebruiken, heb ik aan het begin van de code `if(document.querySelector){` staan. Als querySelector namelijk niet ge-support wordt, dan heb ik dus basis HTML en CSS als fallback.    
 ## Browsertest
 Ik heb mijn lijstje op meerdere browsers getest. Over het algemeen zag het er goed uit. Het kwam soms door dat bepaalde stijlingen niet helemaal goed doorkwamen en ik heb zelfs gemerkt dat er op 1 device zowel de CSS als de JS het niet deed. 
 
 ### Xperia Z5
 ![experia test][xperia1]
 
 ### LG G5
 
 ### ipad mini 3
 
 ### iPhone 5s
 
 
 
 ## Conclusie
 Mijn boodschappen-om-tostis-te-maken lijstje is toegankelijk voor 100% van de internet gebruikers. Ik heb dit getest op meerdere browsers/devices.
 
 ### Beoordelingscriteria
- [x] De code staat in een repository op GitHub
- [x] Er is een Readme toegevoegd met daarin beschreven:
  - [x] een beschrijving van de core functionality
  - [x] een beschrijving van de feature(s)/Browser Technologies
  - [x] welke browser de feature(s) wel/niet ondersteunen
  - [x] een beschrijving van de accessibility issues die zijn onderzocht
- [x] De demo is opgebouwd in 3 lagen, volgens het principe van Progressive Enhancement
- [x] De user experience van de demo is goed
  - [x] de leesbaarheidsregels zijn toegepast, contrast en kleuren kloppen
  - [x] het heeft een gebruiksvriendelijke interface, met gebruikmaking van affordance en feedback op de interactieve elementen
  - [x] met meest 'enhanced' versie is super vet, gaaf en h-e-l-e-maal te leuk om te gebruiken
- [x] Student kan de Basic functionaliteit van een use case doorgronden
- [x] Student kan uitleggen wat Progressive Enhancement en Feature Detectie is en hoe dit toe te passen in Web Development

[xperia1]: xperia.png
