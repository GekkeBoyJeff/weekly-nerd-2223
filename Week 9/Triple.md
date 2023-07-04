Dit college word gegeven door Chanel, zij is een front-end developer. Een oud CMD student die de minor Web Design en Development heeft gevolgd.
Zij is afgestudeerd in 2018 en is direct begonnen bij triple. Zij maken digital experiences, ze doen aan hosting, gadgets, smart-tv applicaties en maken native apps. Het is best een divers bedrijf. In een korte periode zijn zij enorm gegroeid en hebben zij meerdere bedrijven overgenomen.

Hun klanten zijn: MaxVerstappen, citizen, ajas, NLZiet, en Heineken.

## Waarom?
Zij heeft hier ook gezeten net als wij nu. zij gaf aan dat de school vaak al keuzes maakt vanuit ons en Chanel wou laten zien hoe het in het bedrijfsleven werkt.

## Hoe ziet een gemiddelde front-end setup eruit bij tripple?

### Basics
1. Git
	1. Gebruik version control vanwege:
		1. Rollback
		2. Debugging
		3. Dan zie je waarom dingen zo zijn geschreven. en je kan aankloppen bij de personen die die stukken hebben geschreven
2. Werkwijze
	1. Create branch
		1. Vanaf main maak je een feature branch, Main is altijd stable.
	2. Commit & push
	3. Create pull request
	4. code naar main
	5. deployment
3. NPM
	1. Soms is iets een betere implementatie dan wat ik zelf zou maken.
	2. Kijk naar de volgende dingen:
		1. Goed onderhouden?
		2. Word ie geupdatet?
		3. Veel downloads geven aan of ie goed is of niet?
		4. Aantal contributers
		5. Package size.
		6. Het liefst een package die indipendent zijn.

### Setup
Als eerste besluit je of je vanila, library of een framework gebruikt.
Alles heeft zijn pro's en cons. maar don't reinvent the wheel. Dit ook omdat klanten vaak snel hun product hebben

De vraag van Triple was: Hoe kunnen we snel schaalbare applicaties maken?
Als SEO niet belangrijk is gebruikte zij react. 
Zij kozen next.Js en Angular.
Sinds kort zijn zij overgestapt naar Svelte.
Svelte is lichter dan react en is makkelijker te leren.

## Early error catching
Hoe vinden we problemen in de code voordat het in de browser te zien is.

Zij gebruiken Typescript. Typescript laat errors zien als je aangeeft wat waarin moet staan.

const first = 5;
const second = '6';
console.log(first+second)

## Code formatting & fixing
Iedere developer heeft graag zijn formatting anders. om dit op één lijn te houden gebruiken zij ESLint en Prettier.

## Css
Zij gebruiken Sass om repetition tegen te gaan. je kan css namelijk nesten.

## Vite
Zij gebruiken Vite om een development op te zetten die out of the box werkt. Het heeft support voor alles wat ze nodig hebben. En als iets word aangepast in je modules word de server automatisch opniet opgestart. 


## Livegang
ze gebruiken FTP. dat is vrij foutloos.

Zij gebruiken Azure en Azure DevOps en zij zorgen dat omgevingen klaarstaan waar ze kunnen pushen om te testen. 
DevOps helpt met het pullen, pipelines en tickets.

Als je je code hebt gepusht is het ongebuild. Pipelines build het, doet wat checks en zet eigenlijk de gehele productie klaar.

## Testversie
### Zij hebben vaak 3 omgevingen
1. Dev omgeving
	1. tester gaat eroverheen
	2. 
2. Acceptatie omgeving
	1. klant kan het bekijken
3. PROD omgeving

