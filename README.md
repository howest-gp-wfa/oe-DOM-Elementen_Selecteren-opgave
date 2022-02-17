# Variabelen en DOM-elementen
## Werking
### Opstarten
- In inpId wordt de tekst 'inpNaam' ingevuld
- In inpCssSelector wordt de tekst 'label' ingevuld
- Bij een klik op 'btnHideElementById' wordt de function 'hideShowElementById' uitgevoerd
- Bij een klik op 'btnHideElementBySelector' wordt de function 'hideShowElementBySelector' uitgevoerd
### function hideShowElementById
Via de input in inpId wordt afhankelijk van de zichtbaarheid van het element met het ingetikte id:
- indien zichtbaar: 
  * element wordt verborgen
  * in divFeedback verschijnt de tekst: 'Je hebt het volgende element verborgen: ' gevolgd door het verborgen element
  * de tekst in btnHideElementById wordt veranderd in 'Toon element met id'
- indien verborgen:
  * element wordt terug zichtbaar
  * in divFeedback verschijnt de tekst: 'Daar is ie weer: ' gevolgd door het zichtbaar gemaakte element
  * de tekst in btnHideElementById wordt veranderd in 'Verberg element met id'
  
### function hideShowElementBySelector

Programmeer dezelfde functionaliteiten voor btnHideElementBySelector via de input in txtCssSelector. 
Hier wordt het te verbergen/tonen element via de css-selector geselecteerd.

De tekst in de button staat op 2 lijnen.

Denk na over de declaratie, invulling en scope van de variabelen
Waar kun je eventueel constants gebruiken?
