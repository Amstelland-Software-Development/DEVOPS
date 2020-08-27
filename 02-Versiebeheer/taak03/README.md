# DEVOPS-TAAK-NR03

## Repositories, local & remote en Git Clone

## Uitleg

Het is belangrijk dat je alvast de terminologie die gebruikelijk is in Git leert kennen. In deze taak gaan we leren wat een Git Repository is.

Je bent misschien al gewend om met bestanden en mappen te werken in Windows of op een Mac. Wat Git doet is een laagje daarover heen gooien zodat Git zijn werk kan doen. 

Op het moment dat je een map hebt met daarin de bestanden waarin je code schrijft, de zgn broncode, kun je Git de opdracht geven om de veranderingen in deze bestanden bij te houden. Wat Git dan doet is een submapje aanmaken genaamd `.git`. Dit is standaard een verborgen map en je hoeft daar zelf niks mee te doen verder. Het programma Git beheert dit mapje, later meer daarover.

> DEFINITIE: Binnen de Git terminologie noem je zo'n map met broncode die beheerd wordt door Git een **Repository**.

Zo'n zgn repository kan bestaan op je laptop (**local**) of gehost worden door een online dienst zoals Github (**remote**). 

Wat we in deze taak gaan doen is het downloaden van een op Github gehoste repository naar jouw laptop.
> DEFINITIE: het downloaden van de bestanden (*én versie geschiedenis!*) van een repository noem je in Git terminologie **Clonen**.

## Leerdoelen

1. Ik kan in 2 zinnen uitleggen wat er bedoeld wordt met een Git Repository.
2. Ik kan een clone maken van een remote repository

## Opdracht

1. Ga naar Github.com en log in. Als het goed is staat er een repository genaamd DEVOPS onder je account. Open die repository (door op de naam te klikken) en zoek naar de groene CODE knop, als je daarop klikt kun je een link kopieren. De link ziet er ongeveer zo uit: `https://github.com/<jouw github account naam>/DEVOPS.git` en eindigt op `.git`.
2. Als je dat nog niet hebt gedaan maak een map aan op je onedrive genaamd b.v. jaar1. (In deze map komen de bestanden van alle modules die je gaat doen). Open VS Code en open de net aangemaakt map. Open in VS Code een nieuwe terminal en voor het onderstaande commando uit:
```cmd
git clone https://github.com/<jouw github account naam>/DEVOPS.git
```
3. Als Git goed zijn werk doet maakt Git een submap aan genaamd DEVOPS met daarin al het lesmateriaal voor deze module.
4. Open nu in VS Code alleen de net aangemaakte map genaamd DEVOPS. Ga naar je Project Manager tab in de Activity Bar en sla deze map op als favoriet project. 

## Eindresultaat

Je hebt een map onder je onedrive map staan genaamd `jaar1` met daarin een submap genaamd `DEVOPS` met daarin al het lesmateriaal voor deze module. Daarnaast heb je een favoriet project aangemaakt via de Project Manager zodat je snel deze module kunt openen in VS Code.

## Bronnen

Geen Project Manager geinstalleerd? Kijk bij `01-VS-code\Taak04` om dit alsnog te doen.