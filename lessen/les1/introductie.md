# Introductie
In deze cursus gebruiken we een aantal tools:

- Command Line Interface (CLI) (tekstgebaseerde instructieregels)
- Python Interpreter
- Visual Studio Code (code editor)
- Github (online versiebeheer)
- Git (versiebeheersysteem)


## Command Line Interface (CLI)

Met de command line kunnen we via de zogenaamde Terminal opdrachten aan de computer geven.

Openen van de Terminal:

- Open het windows menu en type in 'cmd' en kies voor 'Command Prompt'

Dit open de powershell of in sommige gevallen nog een oude DOS prompt. 
Hier kun je verschillende commando's gebruiken om bijvoorbeeld de inhoud van je harde schijf te zien:

- ls (powershell) of dir (DOS)

Je krijgt mappen te zien. Om in een van de mappen te komen, kun je een ander commando gebruiken:

- cd

Doe bijvoorbeeld cd \<mapnaam> en daarna nog een keer ls en je krijgt nu de inhoud van \<mapnaam> te zien.



## Python Interpreter

Om Python te programmeren heb je een zogenaamde interpreter nodig. Dit is een programma dat de Python instructies kan vertalen naar machinecode om op de computer uit te voeren. Dit gebeurt in realtime, dus is het wat langzamer dan andere soorten programmeertalen die van tevoren vertaald zijn.

- Installeer de Python interpreter

Ga naar https://www.python.org/downloads/ and download de Python versie voor jouw computer en installeer deze. 

Als het is geinstalleerd, kun je in de command line Python programmeren.

Open een nieuwe command line en type:
- python --version

Hiermee krijg je het geinstalleerde versienummer van Python te zien. Het kan zijn dat Python nog niet werkt in jouw command line. Dit komt waarschijnlijk doordat het nog niet in je pad staat. Om dit in Windows op te lossen kun je de bijvoorbeeld de volgende stappen proberen: https://phoenixnap.com/kb/add-python-to-path



## Visual Studio Code

Omdat het programmeren van Python in de command line nogal kaal en onhandig is, maken we gebruik van een code editor. In deze cursus gebruiken we de populaire code editor Visual Studio Code.
- Installeer Visual Studio Code

Ga naar https://code.visualstudio.com/ en download de VS Code versie voor jouw computer installeer deze.

Als het is geinstalleerd:
- maak een nieuwe map aan op jouw computer
- open deze map met VS Code

Maak een nieuw tekstbestand aan genaamd 'readme.txt' en type hierin 'Dit is mijn Python project'

## Github
Github is een online platform voor softwareontwikkeling en versiebeheer.
- maak een github account aan

Ga naar https://github.com/ en klik op 'Sign Up'en volg de instructies.

### Aanmaken github credentials in VS Code
user en password

voor meer informatie zie: https://www.geeksforgeeks.org/how-to-add-git-credentials-in-vscode/

## GIT

GIT is een versiebeheersysteem waarmee je code versie kunt beheren. Daarnaast kun je hiermee samenwerken met andere developers. Git is geintegreerd in Visual Studio Code waarvan wij ook gebruik van gaan maken.

- installeer GIT (een versiebeheersysteem) 

Ga naar https://git-scm.com/downloads en download de git versie voor jouw computer en installeer deze

Met Git en VS Code kun je een aantal acties uitvoeren om versiebeheer te gebruiken (git moet wel geinstalleerd zijn):

Open VS Code met jouw map geopend.

klik op het 3e icoontje (onder het vergrootglas) aan de linkerzjkant in de toolbalk. Je ziet twee blauwe knoppen 'Initialize Repository' en 'Publish to Github'

### git init
Om je eigen nieuwe repository te maken klik op 'Initialize Repository'

### git commit
Type vervolgens in de input balk onder 'Source control' 'Nieuwe repository' in en klik op de blauwe knop 'Commit'. Klik op 'yes' of 'always' als gevraagd wordt of je al je veranderingen wilt opslaan. De eerste versie van jouw repository is nu opgeslagen.

### git push

Klik vervolgens op Publish Branch enkies voor 'Publish to GitHub public repository

## (Optioneel)
### git pull
Als de code op Github in een hogere versie zit dan jouw lokale versie, kun je een zogenaamde 'git pull' doen om de laatste veranderingen op te halen.

### git clone
Als je een project van Github lokaal op je computer wilt. kun je deze clonen.



