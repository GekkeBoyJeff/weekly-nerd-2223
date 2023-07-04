# Chanel: De Front-End Developer die de wereld van Triple onthult

Chanel, een front-end developer en oud CMD-student die de minor Web Design en Development heeft gevolgd, gaf onlangs een college. Na haar afstuderen in 2018, sprong ze direct in de digitale wereld met Triple, een bedrijf dat zich specialiseert in het creëren van digitale ervaringen. Van hosting tot gadgets, smart-tv applicaties en native apps, Triple is een divers bedrijf dat in korte tijd aanzienlijk is gegroeid en meerdere bedrijven heeft overgenomen. Met klanten zoals Max Verstappen, Citizen, Ajax, NLZiet en Heineken, heeft Triple een sterke voet in de markt gezet.

## Een Kijkje Achter de Schermen bij Triple

Chanel, die ooit op dezelfde plek zat als de huidige studenten, wilde laten zien hoe het bedrijfsleven werkt, een perspectief dat vaak ontbreekt in het reguliere curriculum. Dus hoe ziet een gemiddelde front-end setup eruit bij Triple?

### De Basisprincipes

#### Git

Het begint allemaal met Git, een version control systeem dat wordt gebruikt om meerdere redenen:

1. Rollback: Als er iets misgaat, kunt u terugkeren naar een vorige versie.
2. Debugging: Het helpt bij het opsporen van fouten.
3. Begrip: Het geeft inzicht in waarom dingen op een bepaalde manier zijn geschreven.

#### Werkwijze

De werkwijze bij Triple is als volgt:

1. Create branch: Begin met het maken van een feature branch vanaf de main branch, die altijd stabiel moet zijn.
2. Commit & push: Verzeker je van een goede commit en push deze naar de repository.
3. Create pull request: Maak een pull request om je wijzigingen te laten beoordelen.
4. Merge code naar main: Voeg je wijzigingen toe aan de main branch.
5. Deployment: Deploy de veranderingen.

#### NPM

Het gebruik van NPM is ook essentieel. Ze kijken altijd naar het onderhoud van een package, of het wordt geüpdatet, het aantal downloads, contributors, de package size en of het onafhankelijk is.

### De Setup

Bij het opzetten van een project besluit je eerst of je vanila, een library of een framework gebruikt. Alles heeft zijn voor- en nadelen, maar de belangrijkste regel is: don't reinvent the wheel. Triple koos voor next.Js en Angular, en zijn onlangs overgestapt naar Svelte, dat lichter is dan React en makkelijker te leren.

## Foutopsporing en Code Formatting

Triple maakt gebruik van TypeScript voor early error catching en ESLint en Prettier voor code formatting & fixing. Ze gebruiken Sass om repetition tegen te gaan en Vite om een development op te zetten die out of the box werkt.

## De Livegang

Bij het live gaan, gebruiken ze FTP, wat vrij foutloos is. Ze maken gebruik van Azure en Azure DevOps, die omgevingen klaar hebben staan waar ze kunnen pushen om te testen. DevOps helpt met het pullen, pipelines en tickets.

## Testversies

Bij Triple is er een gestructureerde aanpak voor het testen en live brengen van applicaties, met een systeem van drie verschillende omgevingen:

1.  **Dev Omgeving**: Hier wordt de eerste ronde van tests uitgevoerd. Een tester zal de code grondig doornemen om eventuele problemen op te sporen en op te lossen.
    
2.  **Acceptatie Omgeving**: Na de Dev omgeving wordt de code verplaatst naar de Acceptatie omgeving. In deze fase kan de klant de applicatie bekijken en feedback geven.
    
3.  **PROD (Productie) Omgeving**: Ten slotte wordt de code naar de productieomgeving verplaatst, waar het live gaat voor de eindgebruikers. Deze omgeving moet altijd stabiel en foutloos zijn.
    

Dit proces zorgt ervoor dat eventuele problemen vroegtijdig worden opgemerkt en opgelost, en dat de eindproducten altijd van de hoogste kwaliteit zijn.

# Chanel: De Front-End Developer die de wereld van Triple onthult

Chanel, een front-end developer en oud CMD-student die de minor Web Design en Development heeft gevolgd, gaf onlangs een college. Na haar afstuderen in 2018, sprong ze direct in de digitale wereld met Triple, een bedrijf dat zich specialiseert in het creëren van digitale ervaringen. Van hosting tot gadgets, smart-tv applicaties en native apps, Triple is een divers bedrijf dat in korte tijd aanzienlijk is gegroeid en meerdere bedrijven heeft overgenomen. Met klanten zoals Max Verstappen, Citizen, Ajax, NLZiet en Heineken, heeft Triple een sterke voet in de markt gezet.

## Een Kijkje Achter de Schermen bij Triple

Chanel, die ooit op dezelfde plek zat als de huidige studenten, wilde laten zien hoe het bedrijfsleven werkt, een perspectief dat vaak ontbreekt in het reguliere curriculum. Dus hoe ziet een gemiddelde front-end setup eruit bij Triple?

### De Basisprincipes

#### Git

Het begint allemaal met Git, een version control systeem dat wordt gebruikt om meerdere redenen:

1. Rollback: Als er iets misgaat, kunt u terugkeren naar een vorige versie.
2. Debugging: Het helpt bij het opsporen van fouten.
3. Begrip: Het geeft inzicht in waarom dingen op een bepaalde manier zijn geschreven.

#### Werkwijze

De werkwijze bij Triple is als volgt:

1. Create branch: Begin met het maken van een feature branch vanaf de main branch, die altijd stabiel moet zijn.
2. Commit & push: Verzeker je van een goede commit en push deze naar de repository.
3. Create pull request: Maak een pull request om je wijzigingen te laten beoordelen.
4. Merge code naar main: Voeg je wijzigingen toe aan de main branch.
5. Deployment: Deploy de veranderingen.

#### NPM

Het gebruik van NPM is ook essentieel. Ze kijken altijd naar het onderhoud van een package, of het wordt geüpdatet, het aantal downloads, contributors, de package size en of het onafhankelijk is.

### De Setup

Bij het opzetten van een project besluit je eerst of je vanila, een library of een framework gebruikt. Alles heeft zijn voor- en nadelen, maar de belangrijkste regel is: don't reinvent the wheel. Triple koos voor next.Js en Angular, en zijn onlangs overgestapt naar Svelte, dat lichter is dan React en makkelijker te leren.

## Foutopsporing en Code Formatting

Triple maakt gebruik van TypeScript voor early error catching en ESLint en Prettier voor code formatting & fixing. Ze gebruiken Sass om repetition tegen te gaan en Vite om een development op te zetten die out of the box werkt.

## De Livegang

Bij het live gaan, gebruiken ze FTP, wat vrij foutloos is. Ze maken gebruik van Azure en Azure DevOps, die omgevingen klaar hebben staan waar ze kunnen pushen om te testen. DevOps helpt met het pullen, pipelines en tickets. Zodra je je code hebt gepusht in zijn ongebouwde staat, bouwen de pipelines het, voeren wat checks uit en zetten de gehele productie klaar.

## De Testomgevingen

Triple hanteert meestal drie omgevingen:

1. **Dev omgeving**: Hier gaat de tester overheen.
2. **Acceptatie omgeving**: Hier kan de klant het bekijken.
3. **PROD omgeving**: De productieomgeving waar de live versie van het product draait.

Met deze drie omgevingen kan Triple ervoor zorgen dat alle bugs en problemen worden opgelost voordat de software live gaat. Het stelt hen ook in staat om feedback van klanten te krijgen in de acceptatieomgeving voordat ze naar productie gaan.

Hiermee wordt een einde gemaakt aan de fascinerende reis door de wereld van Triple zoals gepresenteerd door Chanel. Haar verhaal geeft een waardevol inzicht in de processen en procedures van het bedrijfsleven en hoe het verschilt van de academische wereld.