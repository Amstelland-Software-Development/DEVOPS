# DEVOPS-TAAK-NR05

## Terminal & Problems Panel

## Uitleg

### Problems Panel 

VS Code helpt je graag met het schrijven van je code. Als er problemen zijn met je code dan kan je die vinden in het Problems Panel (<kbd>CTRL</kbd>+<kbd>SHIFT</kbd>+<kbd>M</kbd>) onder in VS Code.

Als je deze bekijkt dan probeert VS Code zo goed mogelijk te beschrijven wat er niet klopt in de code. Als het goed is zie je de onderstaande regel in het Problems Panel:
```
script.js[4,36] The parser expected to find a '}' to match the '{' token here.
```
> Als je op zo'n melding klikt springt je cursor naar een bepaalde plek in het `script.js` bestand.

De melding zelf is als je net begint te programmeren vaak lasting te interpreteren. In dit geval gaat het om een stukje code dat twee getallen bij elkaar optelt. VS Code begrijpt niet wat jij wilt doen met je code maar kan wel aangeven dat er ergens een stukje syntax niet klopt.

Dit is vergelijkbaar met de spellings check van bijvoorbeeld een verhaal dat je schrijft in Word. De spelchecker kan aangeven dat je een bepaald woord niet goed hebt geschreven (je vergeet een letter) maar zegt niks over of het verhaal wat je schrijft qua inhoud (werking van het programma) wel logisch is. 

> TIP: Net zoals in Microsoft Word bij spelfouten zet VS Code een rode indicator (~) onder de code waar zich volgens VS Code een fout bevindt. Als je met je muis over die indicator beweegt zie dezelfde boodschap zoals die in het Problem Panel zichtbaar is. 

Maar wat kan je daar nu uit afleiden zodat je de fout kan herstellen? 

### Terminal

Je opent een nieuwe terminal door uit de menu balk te kiezen voor `Terminal > New Terminal` of de sneltoets <kbd>CTRL</kbd>+<kbd>SHIFT</kbd>+<kbd>`</kbd>. 

De Terminal is de plek binnen VS Code waar je getypte commandos kan uitvoeren. Dit gebruik je o.a. voor het uitvoeren van commandos voor versiebeheer met Git, hierover later meer. Voor nu is het alleen belangrijk dat je weet hoe je een nieuwe terminal opent binnen VS Code.

## Leerdoelen

1. [ ] Ik kan het Problems Panel openen en problemen met mijn code opsporen.
2. [ ] Ik kan een nieuwe terminal openen en een commando uitvoeren

## Opdracht

1. Open `script.js` in VS Code en open daarna het Problems Panel. Als je de inhoud van `script.js` bekijkt zie je dat deze uit 10 regels code bestaat. In het Problems Panel staat dat er 1 probleem gevonden is met deze code. Zorg ervoor dat je dit probleem oplost.
   > TIP: je kunt door met je rechtmuisknop op de melding in het Problems Panel te klikken ervoor kiezen om de melding te kopieren. Zo kun je snel zoeken op internet naar die specifieke foutmelding.
2. Open een nieuwe Terminal. In het Terminal Panel type de volgende commandos in en druk op <kbd>Enter</kbd> om ze uit te voeren:
   1. dir 
    > toont een lijst bestanden in een map
   2. cd..
    > Gaat een map omhoog in de bestandsstructuur
   3. cd 
    > verander van map. Gebruik <kbd>TAB</kbd> voor autocomplete.
   4. cls
    > Clear screen. Wist het scherm. 

## Eindresultaat

## Bronnen