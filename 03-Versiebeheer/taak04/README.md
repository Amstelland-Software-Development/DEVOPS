# DEVOPS-TAAK-NR04

## Working directory, stage en local repository

## Uitleg

Je kunt nu de inhoud van een repository die op Github staat kopieren naar je laptop. 

> In Git termen: je cloned een remote repo naar een local repo.

In deze taak houden we het simpel. We leggen alleen uit hoe Git kijkt naar de bronbestanden waarin je werkt en gaan een nieuwe bestand toevoegen aan de repository van deze module. 

Voor de komende taken gebruiken we het onderstaande schema om een visueel beeld te geven van de verschillende handelingen die je via Git gaat uitvoeren. Het lijkt ingewikkeld maar we gaan dit stapje voor stapje doen en in het begin beperken we ons maar tot een paar handelingen.

![](/02-Versiebeheer/taak04/gfx/git-workflow.png)

### Working Directory

Links boven in bovenstaand schema zie je in groen de term Working Directory staan. Een directory is een ouderwetse engelse benaming voor een folder oftewel map. De Working Directory is dus de map waarin je op dit moment aan het werk bent.

Als je een bestaande repository opent zoals deze van de DEVOPS module dan is Git al op de hoogte van het bestaan van alle bestanden in de Working Directory. De bestanden worden door Git *getracked*'. Maar wat als je een nieuw bestand aanmaakt? 

Een bestand dat voor Git nieuw is moet handmatig worden toegevoegd aan de repository. Dit toevoegen van een bestand doe je door het `git add` commando gevolgd door de bestandnaam uit te voeren in de terminal binnen VS Code. Maar dit kan gemakkelijker via de VS Code user interface door te kijken in het Source Control paneel <kbd>CTRL</kbd>+<kbd>SHIFT</kbd>+<kbd>G</kbd>.

Hier zie je een lijst van alle bestanden in je Working Directory waarvan Git heeft gemerkt dat je er iets aan veranderd hebt, zie onderstaand voorbeeld.

![Source Control panel](/02-Versiebeheer/taak04/gfx/vs-code-source-control-panel.jpg) 

In bovenstaand voorbeeld zie je onder het kopje `changes` twee bestanden staan: `README.MD` met daarachter een gekleurde M (die staat voor Modified; Aangepast in het nederlands) en een tweede bestand genaamd `nieuw-bestand.txt` met daarachter een U (die staat voor Untracked; niet gevolgd). 

Als je op het plusje klikt naast de bestandsnaam van het `nieuw-bestand.txt` bestand waarvan Git dus nog niet de versiegeschiedenis bijhoudt dan voeg je dit bestand toe aan de index (lijst van bestanden) die Git voor je bijhoudt. In Git termen *stage* je de bestanden. Zie onderstaand voorbeeld om te zien hoe het eruit ziet in VS Code als je een het `nieuw-bestand.txt` bestand heb toegevoegd aan de `stage` (of zoals het in het schema wordt genoemd: de Staging Area).

![Source Control add file](/02-Versiebeheer/taak04/gfx/vs-code-added-file.jpg)

> LETOP: Dit bestand is dan nog niet opgenomen in je lokale repository, daarvoor moet je nog één belangrijke stap doen.

Git kan de veranderingen in honderden tot vele duizenden bestanden efficient voor je bijhouden maar dat wil niet zeggen dat jij zelf op basis van die veranderingen goed kan zien met welke versie van een bepaald bestand je te maken hebt. Laat staan wanneer het gaat om veranderingen van meerdere bestanden samen. Daarom schrijf je altijd een kort stukje tekst, een zgn Commit Message als je bestanden toevoegd aan een repository. Op basis van die commit message kan jij dan zien wat er veranderd is. Het is dus belangrijk dat je een heldere, duidelijke beschrijving geeft van de verandering. In dit geval is de ongeschreven regel dat een Commit Message schrijft zoals `added nieuw-bestand.txt` of `added new text file`. 

Als je een korte bondige Message hebt bedacht en je op het vinkje boven aan het Source Control paneel klikt dan wordt alles wat er op dat moment *gestaged* is toegevoegd aan je lokale repository. We kunnen dan weer aan de slag met coderen en mochten we echt van alles door de war schoppen dan kan je altijd weer terug naar staat van de bestanden zoals die was toen je ze toevoegde aan de repository.

Nog een laatste Git term: het toevoegen van bestanden die je hebt klaargezet in de Staging Area toevoegen aan de repository noem je *commiten* (toevertrouwen in het nederlands). Zo'n verzameling van bestanden in een bepaalde staat (versie) noem je een *Commit*. 

> Ok. Dit was erg veel informatie en als je dit allemaal netjes hebt doorgelezen, petje af! Maak je geen zorgen als het niet meteen op z'n plek valt allemaal, dit gebeurt wel zodra je er meer mee werkt. 

### Samenvatting

* `commit` een snapshot van de inhoud van 1 of meer bestanden
* `stagen` 
* `Working Directory` de map waarin alle bestanden in staan waarin je programmeert
* `stage` een plek om b 

## Leerdoelen

1. Ik weet wat binnen de Git bedoeld wordt met de Working Directory
2. Ik weet wat binnen de Git bedoeld wordt met de Staging Area
3. Ik weet wat binnen de Git bedoeld wordt met de Local Repository

## Opdracht

1. Maak in de taak04 map een nieuw bestand aan genaamd `nieuw-bestand.txt`. Kijk in je Source Control paneel en voeg dit bestand toe aan de stage. Schrijf als commit message `eerste bestand gestaged` en voeg het bestand toe aan de repository door op het vinkje te klikken.

## Eindresultaat

## Bronnen
