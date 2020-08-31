# DEVOPS-TAAK-NR02

## Git & Github

**LETOP: ook als je Git al hebt geinstalleerd: lees de onderstaande taak goed door en zorg ervoor dat alles werkt zoals verwacht wordt.**

## Uitleg

Het werken met een versiebeheer systeem zoals Git is vaak in het begin verwarrend. Dat is helemaal Ok, de ervaring leert dat het werken met Git vooral duidelijk wordt wanneer je het echt zelf gaat gebruiken.

Wel is het belangrijk dat je goed weet hoe wat het verschil is tussen Git en Github.

**Git** is de software die voor jou het versiebeheer doet. Dit gaan we installeren op je laptop en deze draait dan lokaal net als bijvoorbeeld Word en Excel als je die hebt geinstalleerd. Github is een online dienst net als bijvoorbeeld Facebook. Zo'n dienst draait op een server (computer) die je kan benaderen via internet mbv een webbrowser. Op dezelfde manier als dat je Word en Excel kan draaien in je browser via Office365.

> DUS: Git is de software, Github is de dienst.

Github is een online dienst waarmee je samen kan werken aan het ontwikkelen van software. De code die schrijft en lokaal op jouw laptop wordt opgeslagen kun je synchroniseren met Github. Zo kan een docent meekijken naar het werk dat je voor jouw opleiding doet maar is het straks als je op zoek gaat naar een stageplek of aan de slag gaat als ontwikkelaar na je opleiding ook een plek waar zij kunnen zien wat je allemaal hebt gedaan op qua software ontwikkeling.

Opvolgende taken in deze module maken je wegwijs in de werking van Git en Github maar voor nu gaan we beginnen met het installeren van Git, wat instellingen doen en een account aanmaken op Github.

## Leerdoelen

1. Ik heb Git geinstalleerd en werkend binnen VS Code.
2. Ik kan een account aanmaken op Github en inloggen.

## Opdracht

1. Ga naar https://git-scm.com/ en download en installeer de versie van Git voor jou computer.
    > LETOP: er worden nogal wat dingen gevraagd tijdens de installatie. Kies voor de standaard opties tenzij je weet wat je doet.

    Is het gelukt? Open (of heropen) VS Code, open een nieuwe terminal en voor het onderstaande command uit: `git` <kbd>enter</kbd>

    > Als het goed werkt krijg je een lap tekst met uitleg over hoe je Git gebruikt via de command line.
2. Git wil graag weten wie bepaalde code heeft geschreven. Hiervoor moeten we twee instellingen doen via de command line:
    
    Open een nieuwe terminal in VS Code en voer de 2 onderstaande commandos uit:
   
    ```cmd
    git config --global user.name = "Je voornaam en achternaam"
    ```
    en
    ```cmd
    git config --global user.email = "voornaam.achternaam@student.rocva.nl"
    ```
    > LETOP: Vul dus tussen de `"` en `"` jouw gegevens in. Dus als voorbeeld:  

    > git config --global user.name = "Bill Gates" <kbd>enter</kbd>  
    > git config --global user.email = "bill.gates@student.rocva.nl" <kbd>enter</kbd>
3. Ga naar [Github](http://www.github.com) en maak een nieuwe account aan, letop: lees onderstaande punten goed door en hou je daar aan:
   > Punt 1: Kies een representatieve naam. Deze naam gaat gezien worden door de mensen die straks beslissen of jij een stageplek of baan krijgt, kies bij voorkeur een accountnaam die bestaat uit je voornaam en achternaam.  

   > Punt 2: gebruik je voornaam.achternaam@student.rocva.nl mail account om je aan te melden. 

## Eindresultaat

Je hebt Git geinstalleerd op je laptop en als je dit test binnen een terminal in VS Code zie dat als jet `git` als commando uitvoert geen foutmeldingen. Je hebt een account aangemaakt op Github en je kunt inloggen.

## Bronnen

[Instellen naam en email in Git](https://linuxize.com/post/how-to-configure-git-username-and-email/)  
[Github account aanmaken uitleg](https://www.wikihow.com/Create-an-Account-on-GitHub)