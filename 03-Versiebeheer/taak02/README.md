# DEVOPS-TAAK-NR05

## Git en Repositories

## Uitleg

In deze taak gaan we leren wat een **Git-Repository** is.

Je bent misschien al gewend om met bestanden en mappen te werken in Windows of op een Mac. Je kunt Git zien als een laagje daarbovenop dat voor jou het versiebeheer doet. 

Git kent een aantal concepten en handelingen die lijken op wat je al kent als je met bestanden hebt gewerkt, zoals opslaan en kopieren, maar die hebben wel binnen Git een eigen naam  gekregen. Het is belangrijk dat je alvast de terminologie die gebruikelijk is in Git leert kennen maar maak je geen zorgen, we beginnen alleen met de dingen die je nodig hebt om goed te kunnen werken met Eagle.

### Wat is een repository?

Op het moment dat je een map hebt met daarin de bestanden waarin je code schrijft, de zgn *broncode*, kun je Git de opdracht geven om de veranderingen in deze bestanden bij te houden. Zo'n verzameling mappen en bestanden waarvan Git de versies bijhoudt noem je een **Repository**.

> Wat Git dan doet is een submapje aanmaken genaamd `.git`. Dit is standaard een verborgen map en je hoeft daar zelf niks mee te doen. Git beheert de inhoud van dit mapje voor je en wij vertellen Git wat het moet doen.

**DEFINITIE**: Binnen de Git-terminologie noem je zo'n map met broncode die beheerd wordt door Git een **Repository**.

### Wat doet Git met repositories?

Git houdt dus voor je bij hoe een bestand in de loop van tijd verandert. Je kunt dan altijd zien wat, wanneer en door wie iets is aangepast of zelfs teruggaan naar een oudere versie van je code.

Een repository kan bestaan op je laptop (**local**) of gehost worden door een onlinedienst zoals Github (**remote**). Lokaal houdt de versie van Git die je hebt geïnstalleerd op je laptop de veranderingen bij en op Github draait (min of meer) dezelfde versie van Git die dat doet voor de repositories op Github.

Als je een bepaalde versie van de bestanden in een project opslaat in je lokale repository, dan kun je tegen Git zeggen dat hij deze moet synchroniseren met de onlineversie van die repository.

## Leerdoelen

1. Ik weet wat een repository is
2. Ik weet in VS Code waar ik kan vinden welke bestanden zijn veranderd 

## Opdracht

> Als het goed is heb je bij 01-Eagle/taak02 een clone gemaakt van deze module-repository. (Als je dat nog niet hebt gedaan doe dat dan eerst)
 
1. Open de map die bij deze module hoort in VS Code. Ga naar het `Source-Control`-paneel door dit te kiezen uit de Activity Bar links of door de sneltoets <kbd>CTRL</kbd>+<kbd>SHIFT</kbd>+<kbd>G</kbd>
2. In dit paneel zie je alle veranderingen die door Git zijn opgemerkt. Ga terug naar de File-Explorer en maak een nieuw bestand aan in de map `03-versiebeheer/taak02` genaamd `test.txt`.
3. Check in het Source-Control-paneel of Git dit nieuwe bestand heeft opgemerkt. In de volgende taak gaan we leren hoe je zo'n bestand toevoegt aan de Git-Repository.

## Eindresultaat

Je hebt de repository die bij deze module hoort als map open staan in VS Code. Bij het Source-Control-icon op de Activity-Bar is een cijfer te zien dat aangeeft dat er veranderingen zijn.

## Bronnen
