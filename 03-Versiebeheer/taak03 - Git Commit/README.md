# DEVOPS-TAAK-03

## Git Commit

## Uitleg

We hebben al gezien hoe je de bestanden die bij een module horen kan downloaden (clonen) naar je computer. De volgende stap is het toevoegen van de veranderingen die je aanbrengt in de code, die dus nu lokaal staat aan de lokale repository.

### Een commit maken

Wat je dus eigenlijk doet is het opslaan van een bepaalde versie van bestanden in de lokale repository. Zo'n snapshot van de staat van een of meerdere bestanden noem je in Git termen een `commit`. De actie die je daarvoor uitvoert noem je dan ook het `committen` van je code.

Als je aan het werk bent in een project, ben je vaak in meedere bestanden tegelijk bezig en focus je je op wat je aan het maken bent. Als je goed is heb je VS Code zo ingesteld dat deze automatisch bestanden voor je opslaat (of doe je dit zelf constant met <kbd>CTRL</kbd>+<kbd>S</kbd>) én werk je in een onedrive map zodat er ook altijd een versie online staat.

### Commite message

Git kan de veranderingen in honderden tot vele duizenden bestanden efficient voor je bijhouden, maar dat wil niet zeggen dat jij zelf op basis van die veranderingen goed kan zien met welke versie van een bepaald bestand je te maken hebt, zeker wanneer het gaat om veranderingen van meerdere bestanden samen. Daarom schrijf je altijd een kort stukje tekst, een zogenaamde Commit-Message als je bestanden toevoegt aan een repository. Op basis van die commit message kan jij dan zien wat er veranderd is. Het is dus belangrijk dat je een heldere, duidelijke beschrijving geeft van de verandering. In dit geval is de ongeschreven regel dat een Commit-Message schrijft zoals `added nieuw-bestand.txt` of `update index.html`.

Als je een korte bondige Message hebt bedacht en je op het vinkje boven aan het Source-Control-paneel klikt, dan wordt alles wat er op dat moment gestaged is toegevoegd aan je lokale repository. We kunnen dan weer aan de slag met coderen en mochten we echt van alles door de war schoppen, dan kan je altijd weer terug naar staat van de bestanden zoals die was toen je ze toevoegde aan de repository.

LETOP: de veranderingen in je bestanden zijn pas opgeslagen in de repository als je een `commit` hebt gemaakt. De regel als je met Git werkt is: Commit vroeg en commit vaak. Oftewel commit je code voordat hij helemaal af is en doe dit bij voorkeur zo vaak mogelijk.

In deze taak gaan we een eerste commit doen binnen VS Code.

## Leerdoelen

1. Ik kan een commit maken in VS Code

## Opdracht

1. Open het bestand `test.txt` dat in de map van deze taak staat en corrigeer de spelfout. Als het goed is zie je bij het Source-Control-ikoon in de Activity-Bar een tellertje verspringen. Open het Source Control paneel. 
   > Zie onderstaande voorbeeldplaatje: je ziet dat er één bestand te zien is genaamd `test.txt` onder het kopje Changes. Je ziet naast de bestandnaam de map waarin het bestand zich bevindt en helemaal rechts de letter M. Deze staat voor `modified`, oftwel `aangepast`. (als het goed is zie je ook de `test.txt` staan die je hebt aangemaakt in de vorige taak met daarachter een U, dit betekent `untracked`, oftewel `niet gevolgd`. Dit betekent dat Git dit nieuwe bestand nog niet heeft opgenomen in de repository, dat er dus ook geen vroegere versie van bestaat voor zover Git weet. Daarover later meer.) 
   
   ![](/03-Versiebeheer/taak03/gfx/vs-code-commit-message.jpg)
2. Ga naar het Source-Control-paneel en vul als commit-message in: `spelfout gefixt` en druk op het vinkje om een `commit` te maken. 
   > LETOP: VS Code geeft je waarschijnlijk de volgende melding: Klik op `Yes`.

   ![](/03-Versiebeheer/taak03/gfx/vs-code-alert-commit-no-stage.jpg)

3. Je hebt nu je eerste commit gemaakt. Gefeliciteerd. Er zullen er nog velen volgen :) In de volgende taak gaan we kijken hoe je de wijzigingen in jouw lokale repository uploadt naar de repository op Github.


## Eindresultaat

De versie van `test.txt` die in de map van deze taak staat is aangepast zodat de spelfout eruit is gehaald en je hebt deze gecommit in je lokale repository voor deze module.

## Bronnen
