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

Als je op het plusje klikt naast de bestandsnaam van het `nieuw-bestand.txt` bestand waarvan Git dus nog niet de versiegeschiedenis bijhoudt dan voeg je dit best

## Leerdoelen

1. Ik weet wat binnen de Git bedoeld wordt met de Working Directory
2. Ik weet wat binnen de Git bedoeld wordt met de Staging Area
3. Ik weet wat binnen de Git bedoeld wordt met de Local Repository

## Opdracht



## Eindresultaat

## Bronnen
