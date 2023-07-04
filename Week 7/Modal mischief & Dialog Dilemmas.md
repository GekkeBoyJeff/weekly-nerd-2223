# Overlappende Content: Modal Mischief & Dialog Dilemmas

In een hoorcollege, gegeven door toegankelijkheidsexpert Hidde de Vries ([https://www.hidde.blog](https://www.hidde.blog/)), wordt het concept van overlappende content besproken. Waar content oorspronkelijk lineair was, is er tegenwoordig steeds meer sprake van content die elkaar overlapt. Dit komt bijvoorbeeld voor in de vorm van dialogs en popups.

## Terminologie: Modal versus Non-Modal Dialogs

Er is een belangrijk verschil tussen modal en non-modal dialogs. Een modal dialog is een popup die de content voor de pagina plaatst, waardoor je niets anders kunt doen totdat je deze wegdrukt. De focus blijft op de modal. Non-modal dialogs zijn popups waarbij je nog steeds toegang hebt tot de andere content, zoals bijvoorbeeld een deelknop die een menu opent of chatwidgets.

Modal dialogs worden meestal gebruikt voor belangrijke meldingen, zoals bijvoorbeeld een waarschuwing dat de gebruiker binnen 10 minuten wordt uitgelogd.

### Light Dismiss versus Explicit Dismiss

Light dismiss dialogs verdwijnen zodra je buiten het element klikt, terwijl explicit dismiss dialogs niet vanzelf verdwijnen.

### Z-Index versus Top-Layer

Met z-index kun je de lagen van elementen boven of onder een element plaatsen, zoals in het volgende CSS-voorbeeld:

`z-index: top-layer;`

### Backdrop

Een backdrop is een laag achter een element. Bij top-layer elementen kun je de ingebouwde backdrop aanpassen met:

`::backdrop { }`  

### Keyboard Focus Trap

Soms wil je niet dat elementen de tabs blokkeren voor gebruikers die daarmee navigeren, of je wilt juist dat ze binnen een bepaald element worden vastgezet.

## Toepassingen van Dialogs en Popups

### Dialogs

Dialogs worden vaak gebruikt om gebruikers een keuze te laten maken, zoals bijvoorbeeld "Wil je verder?" of "Wil je een nieuw bestand openen?". Modal dialogs maken de content buiten de dialog onbruikbaar en kunnen worden gesloten met de Escape-toets. Dit gebeurt niet bij non-modal dialogs.

Voor het gebruik van een HTML-dialog, kun je de volgende code gebruiken:

`<dialog></dialog>`

Je kunt ook een `role="dialog"` toekennen aan een div-element.

### Popovers

Popovers zijn sets van gedragingen die je kunt toevoegen aan popups die je niet altijd zichtbaar wilt maken. Je laat meestal slechts één popover zien bij het betreffende element. Popovers moeten voorzien worden van de juiste rollen. Ze kunnen worden gebruikt voor datepickers, kalenderwidgets, tooltips, toggletips, en meer.

Popovers worden altijd in de top-layer geplaatst op basis van wanneer je ze aanroept en worden boven op elkaar gestapeld.

### Disclosure Widgets

Een voorbeeld van een disclosure widget is het gebruik van het `<details>` en `<summary>` element:

```HTML
<details>
	<summary>
	</summary>
</details>
```

Dit kan ook met divs worden gedaan, maar dan moet je aria-labels gebruiken.

## Belangrijkste leerpunten
1.  Creëer een blogpagina om je kennis en ervaringen te delen.
2.  Denk goed na over of je een popup modal of non-modal wilt maken, afhankelijk van het doel en de gebruiksvriendelijkheid voor de gebruiker.

