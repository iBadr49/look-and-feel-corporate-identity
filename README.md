> _Fork_ deze leertaak en ga aan de slag. 
Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. 
De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# ViniMini
<!-- Geef je project een titel en schrijf in één zin wat het is --> 
Vini Mini heeft als missie om voedselallergie te voorkomen bij baby’s.

## Opdracht
Ontwerp en maak voor een opdrachtgever een component of website op basis van een bestaande huisstijl. <br>
**Userstory:** Als ouder wil ik in een agenda overzicht krijgen, zodat ik weet op welke dag ik een supplement voor een allergie moet geven.

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->

Ik probeerde een omgeving te bouwen onder de agenda, waar ouders/verzorges kunnen zelf invullen hoe het ging met supplement geven aan hen kind en vinimini laten weten hoe het ging, door dit kunnen ze ook bijhouden wat ze allemaal hebben gedaan en gegeven aan hen kind. <br>
Ik heb ook onze styleguide gevolgd tijdens het bouwen.

<!-- Voeg een mooie poster visual toe 📸 -->

📸 - Hieronder zie je hoe het tot nu eruit ziet. 

-- Hier kan je beschrijven hoe het ging!

![image](https://user-images.githubusercontent.com/112857932/207378646-931ce4bf-94c9-49f9-8427-e6a6cebc0194.png)

-- Hieronder komen er nog andere vragen. (Het idee is nog niet compleet "to  be continued")

<img src="https://user-images.githubusercontent.com/112857932/207378819-1cbc03fd-f0d5-44f6-932f-2144a84e34c3.png" width= 50%>


<!-- Voeg een link toe naar Github Pages 🌐-->

🌐 - link naar mijn Vinimini website is online te vinden op mijn GithubPagina.

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

Om dit te kunnen bouwen, heb ik gebruik gemaakt van Html, Css en een stukje JavaScript. 

JavaScript code die ik heb gebruikt:
```js
const input1 = document.querySelector('.input1');
const inputOn = document.querySelector('.inputOn');
input1.addEventListener("click", inputClick);

// selecteer p element
const paragraph = document.querySelector('.test');

function inputClick(){
    input1.classList.toggle('inputOn');
    paragraph.classList.toggle('test');
}
```

## Bronnen

https://developer.mozilla.org/en-US/  <br>
https://www.w3schools.com/


## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
