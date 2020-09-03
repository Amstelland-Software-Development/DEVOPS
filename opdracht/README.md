# DEVOPS-Eindopdracht

## Eindopdracht Devops

## Uitleg

In de map `website` zit een heel simpele website waar wij wat dingen in gaan aanpassen. De voorbeeldsite bestaat uit de volgende 2 bestanden:
* website\index.html --> de structuur van de site
* website\css\style.css --> de vormgeving van de site

In latere modules leer je meer over hoe HTML en CSS samenwerken om tot een website te komen, maar voor nu onthou alleen dat een .html bestand structuur bevat en dat een .css bestand de vormgeving bepaalt.

Om aan de slag te kunnen moeten we natuurlijk de code aanpassen in VS Code, maar we willen ook het resultaat zien in een browser. Open Chrome en sleep het `index.html` bestand in de map `website` naar een nieuwe chrome-tabblad vanuit de *windows* explorer. (om snel de map `website` te openen zodat je het `index.html`-bestand naar Chrome kan slepen kun je kiezen voor `rechtmuisknop` > `Reveal in File Explorer` of de sneltoets <kbd>SHIFT</kbd>+<kbd>ALT</kbd>+<kbd>R</kbd>)

## Leerdoelen

1. Ik kan bestanden openen in VS Code en eventuele veranderingen opslaan, committen en pushen naar Github.

## Opdracht

> Lees voor je begint de uitleg goed door, zodat je alles klaar hebt staan voor de onderstaande opdrachten.

1. Open `index.html` en zet je eigen naam op de aangegeven plaats in de \<title> tag op regel 6.
2. Ververs de geopende pagina in Chrome met <kbd>CTRL</kbd>+<kbd>R</kbd> en zoek waar je aangepaste tekst terugkomt op de pagina.
3. In VS Code zie dat bij het Source-Control-paneel dat er door Git veranderingen zijn ontdekt in `index.html`. Maak een commit met een duidelijke commit-message (b.v. `title aangepast`) en push je code naar Github. Check online op Github.com of het gelukt is.

4. Vul de website zelf verder aan door drie favoriete films te kiezen en daarvan een plaatje van de filmposter te downloaden. Plaats de plaatjes in de `img` map in de `website` map. De HTML-code die de plaatjes inlaadt, staat in `index.html` op regel 17, 21 en 25. Het geeft niet dat je misschien niet precies begrijpt wat er staat, je kunt nog wel dingen veranderen en kijken wat er gebeurt. Het plaatje dat nu wordt ingeladen heet `voorbeeldposter.jpg` en staat in de `img` map. Vervang de naam `voorbeeldposter.jpg` op de aangegeven regels met de bestandsnamen van de door jou uitgekozen films. (hernoem desnoods de opgeslagen plaatjes eerst naar een makkelijke naar zoals `film1.jpg`, `film2.jpg`, etc). 
5. Ok, als het goed is heb je nu drie plaatjes van je favoriete films zichtbaar als je `index.html` opent in Chrome. (Het geeft niet als de verhoudingen niet helemaal kloppen). Maak een nieuwe commit met een duidelijke commit-message.
6. Je kunt nu ook de titels aanpassen die boven de filmposters staan. Deze staan in `index.html` in een \<h1>-html-element. Doe het onderstaande per film:
   1. Pas de titel van de film aan zodat hij klopt met de getoonde filmposter
   2. Maak een commit met een commit-message die goed beschrijft wat er is veranderd
7. Pas als je alle filmtitels hebt aangepast en dus ook drie commits hebt gemaakt push je je code naar Github. 
8. Tot nu toe heb je alleen in `index.html` gewerkt. Je hebt veranderingen gemaakt in de inhoud van de site. Als laatste gaan we iets aanpassen in `style.css` dat in het `css` mapje staat. Elke filmposter die je hebt gekozen, heeft waarschijnlijk een overheersende kleur. Zorg ervoor dat de omlijning van de posters (die nu blauw is) een kleur krijgt die er beter uitziet als achtergrond van de betreffende filmposter. Als je tevreden bent met het resultaat maak een commit met wéér een goede commit-message die duidelijk omschrijft wat er veranderd is sinds de laatste commit.
9. Als laatste check gaan we kijken hoe het lijstje van jouw commits eruit ziet. Dit kan je zien op Github als je je code hebt gepusht, maar je kan ook kijken wat de laatste commits zijn in je lokale repository. Voer het onderstaande commando uit in een nieuwe Terminal:
    ```cmd
    git log -n 7 --pretty=oneline
    ```



## Eindresultaat

Je hebt een simpele website stap voor stap aangepast zonder dat je misschien wist wat alles betekent, maar door logisch naar de code te kijken en kleine veranderingen door te voeren. Je hebt elke verandering gecommit met een heldere commit-message (zodat je altijd weer terug kan naar die versie) en uiteindelijk je code gepusht naar Github.

## Bronnen

  
