# Variabelen en DOM-elementen
## Werking
### Opstarten
- In id wordt de tekst 'txtNaam' ingevuld
- In css-selector wordt de tekst 'label' ingevuld
- Bij een klik op 'hide-element-by-id' wordt de function 'showAndHideElementById' uitgevoerd
- Bij een klik op 'hide-element-by-selector' wordt de function 'showAndHideElementBySelector' uitgevoerd
### function showAndHideElementById
Via de input in id wordt afhankelijk van de zichtbaarheid van het element met het ingetikte id:
- indien zichtbaar: 
  * element wordt verborgen
  * in feedback verschijnt de tekst: 'Je hebt het volgende element verborgen: ' gevolgd door het verborgen element
  * de tekst in hide-element-by-id wordt veranderd in 'Toon element met id'
- indien verborgen:
  * element wordt terug zichtbaar
  * in divFeedback verschijnt de tekst: 'Daar is ie weer: ' gevolgd door het zichtbaar gemaakte element
  * de tekst in hide-element-by-id wordt veranderd in 'Verberg element met id'
  
### function showAndHideElementBySelector

Programmeer dezelfde functionaliteiten voor hide-element-by-selector via de input in css-selector. 
Hier wordt het te verbergen/tonen element via de css-selector geselecteerd.

De tekst in de button staat op 2 lijnen.

Denk na over de declaratie, invulling en scope van de variabelen
Waar kun je eventueel constants gebruiken?
