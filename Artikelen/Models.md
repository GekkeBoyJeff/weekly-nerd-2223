In de weekly nerd van week 7 heb ik een hoorcollege van Hidde de Vries mogen volgen.
Hidde heeft het over overlappende content gehad en hoe je dit het beste kan gebruiken.  Ik vond het zeer interessant omdat het zo veel simpeler nu is om een popup te maken die je zeer makkelijk kan aanpassen. Hij benoemde tijdens het college  non-modal dialogs en modal dialogs.

## Modal en Non-Modal dialogs
Er zijn twee soorten hiervan: modal en non-modal. Een modal dialog is een pop-up die alles op het achtergrond blokkeert totdat je deze sluit. Een modal dialog is een popup die de content voor de pagina plaatst, waardoor je niets anders kunt doen totdat je deze wegdrukt. De focus blijft op de modal. Non-modal dialogs zijn popups waarbij je nog steeds toegang hebt tot de andere content.

Ik heb modal dialog gebruikt tijdens mijn real-time-web opdracht omdat ik wou dat niks anders in te drukken was. Je kon het dialog sluiten door ernaast te klikken. Dit noemde Hidde een light dismiss.  
![[Pasted image 20230704170257.png]]

## Z-Index, Top-Layer en Backdrop
Dit zijn gewoon elementen van CSS. Z-Index is als een stapel papier, waarbij het hoogste papier de hoogste Z-Index heeft. Top-Layer is het papier helemaal bovenaan de stapel. Een Backdrop is net als een achtergrond voor een element. zoals je hierboven geselecteerd ziet. Het staat boven de content maar heeft wel een achtergrond.

### Backdrop

Een backdrop is een laag achter een element. Bij top-layer elementen kun je de ingebouwde backdrop aanpassen met:

`::backdrop { }`  

## Zelf je dialogs maken
Je kan zelf je dialogs super makkelijk maken. Hier is namelijk een HTML element voor. 

```html
<dialog>
    <!-- Content voor in de dialog -->
</dialog>

<!-- Om de dialog te openen kan je "open" erna neerzetten -->
<!-- Zoals hieronder-->

<dialog open>
    <!-- Content voor in de dialog -->
</dialog>
```

Je kunt ook een `role="dialog"` toekennen aan een div-element.

Om de dialog te openen via javascript gebruik je de volgende code:
```js
const dialog = document.querySelector("dialog")
dialog.show() 
```

Als je ze weer wilt sluiten gebruik je 
```js
dialog.close()
```

## Afsluiting
Models en dialogs zijn enorm interessant. ik ben ook blij dat ik deze heb kunnen toepassen tijdens één van mijn projecten.
Het word ook ondersteund door alle recente browsers wat enorm fijn is.
![[Pasted image 20230704172421.png]]

Dit is zeker iets wat ik in de toekomst zal gebruiken.

Bronnen: 
1. [Dialogs and popovers seem similar. How are they different? | hidde.blog](https://hidde.blog/dialog-modal-popover-differences/)
2. https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog

