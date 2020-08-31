# DEVOPS-TAAK-NR02

## Het lesmateriaal downloaden

## Uitleg

De eeste modules heb je volledig binnen Eagle afgehandeld. Je kon de instructies lezen, de taken uitvoeren en deze afvinken binnen dit systeem. Voor de komende modules zal je echt met programmeren aan de slag gaan en dus code schrijven in verschillende bestanden. Soms krijg je ook code aangeleverd en moet je deze alleen aanpassen, soms moet je nieuwe bestanden aanmaken voor een bepaalde taak. Je levert je code in door deze bestanden te uploaden naar Github. Dit uploaden wordt verzorgd door Git, later in deze module leer je hoe je dit doet.

In deze taak gaan we het lesmateriaal dat bij een module hoort kopieren naar jouw laptop zodat je daar lokaal in kan werken en gemaakt werk kan inleveren.

Dit kopieren van een verzameling bestanden van Github naar jou computer noem je in Git termen *Clonen*. Wanneer je dit doet maakt Git dus een kopie van de bestanden zodat je lokaal kunt werken maar Git snapt ook meteen dat er een link bestaat met de online versie van de bestanden. 

## Leerdoelen

1. Ik kan het lesmateriaal dat bij een module hoort kopieren naar mijn laptop door een Git Clone uit te voeren.

## Opdracht

1. Ga in Eagle naar het module overzicht voor deze module en druk op de knop `Get Clone Link`. (Er wordt nu een link gekopieerd naar je klembord).
2. Maak in onedrive een map aan genaamd: `jaar1`
3. Open VS Code en open de net aagemaakt map in je editor door in de menubalk te kiezen voor `File > Open Folder` of <kbd>CTRL</kbd>+<kbd>K</kbd><kbd>CTRL</kbd>+<kbd>O</kbd> en te bladeren naar de map.
4. Open een nieuwe terminal in VS Code door in de menubalk te kiezen voor `Terminal > New Terminal` of <kbd>CTRL</kbd>+<kbd>SHIFT</kbd>+<kbd>`</kbd>
5. In VS Code opent zich de Terminal onderaan je scherm. Als je deze selecteert dan kun je commandos intypen en uitvoeren. Hierover later meer maar voor nu typ het onderstaande Git commando in en voer deze uit door op <kbd>enter</kbd> te drukken.
   ```cmd
    git clone <link>
   ```
    > In plaats van `<link>` plak je de link die je in stap 1 op je klembord hebt geplaatst. Dit kun je doen door met je rechtmuisknop in het Terminal paneel te klikken of met de sneltoets <kbd>CTRL</kbd>+<kbd>v</kbd>. Ter verduidelijking: het volledige commando ziet er dus ongeveer zo uit: `git clone http://github.com/*****/module.git`
6. Als je op <kbd>enter</kbd> drukt dan wordt het commando uitgevoerd en maakt Git een submap voor je aan met daarin al het lesmateriaal van de module. Als het allemaal goed gaat krijg je een vergelijkbare tekst als hier onder te zien:
   ```
    Cloning into 'basic-it'...
    remote: Enumerating objects: 78, done.
    remote: Counting objects: 100% (78/78), done.
    remote: Compressing objects: 100% (66/66), done.
    remote: Total 169 (delta 38), reused 25 (delta 11), pack-reused 91
    Receiving objects: 100% (169/169), 14.93 MiB | 2.88 MiB/s, done.
    Resolving deltas: 100% (76/76), done.
   ```
   Als je een foutmelding ziet kijk dan of je alle stappen goed hebt gevolgd of vraag een medestudent voor hulp. Kom je er nog niet uit doe dan een hulpverzoek via Eagle.
7. Als laatste stap. Open de aangemaakt map met al het lesmateriaal in VS Code. Als het goed is zie je de bestandsstructuur met al het lesmateriaal in het linker paneel staan en kun je door het lesmateriaal bladeren. Later in deze module gaan we meer leren over VS Code en hoe je via Git en Github werk in kan leveren.

## Eindresultaat

Je hebt een kopie van het lesmateriaal van deze module lokaal staan op je laptop en je kan deze openenen in VS Code. 

## Bronnen
