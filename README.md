# Git 101

# Git?

> Git is een gratis en open-source gedistribueerd versie beheer systeem,
    ontworpen om kleine tot hele grote projecten te beheren met snelheid en
    efficiëntie.

> Git is makkelijk te leren, heeft weinig resources nodig en is super snel. Het
    presteert beter dan andere versie beheer systemen door de ondersteuning van
    lokaal branching, staging areas en meerdere workflows.

_Bron: [git-scm.com]_

Git heeft alleen een commandline interface, er zijn echter diverse tools die met
een grafische interface bovenop Git opereren.

# Git binnen Windows

[Git Extentions], is de meest complete GUI voor windows. Deze heeft bijna alle
Git commando's visueel beschikbaar, integreert met Windows Explorer en biedt een
extensie voor Visual Studio. In deze client staat de visuele weergave van een
Git repository centraal, vanuit deze weergave zijn alle mutaties te zien.

## Aangeraden instellingen

* Git
    * Gebruik Putty voor SSH
    * Checkout Windows-style, commit Unix-style
    * git-cheetah en andere shell extension uitvinken, Git Extentions installeerd
    zijn eigen.
* Git Extentions
    * Kies bij de eerste opstart voor de Engelse taal, hiermee verkom je dat de
    git commando's vernederlandst worden weergegeven.

# Git commando's

## [git init](http://git-scm.com/docs/git-init)

__Maakt een lege Git repository aan.__

### Git Extentions

`rechter muis knop -> GitEx Create new repository...` op of in een map.

![rechter muis knop -> GitEx Create new repository...][init-gitextensions]

## [git commit](http://git-scm.com/docs/git-commit)

__Legt veranderingen vast in de Git repository.__

### Git Extentions

`rechter muis knop -> GitEx Commit...` op of in de Git repository map.

![rechter muis knop -> GitEx Commit...][commit-gitextensions]

## [gitignore](http://git-scm.com/docs/gitignore)

__Specificeert te negeren [untracked bestanden].__

Dit is een tekst bestand binnen de Git repository met alleen de extentie
`.gitignore`. Wildcards kunnen gebruikt worden. Een hele map wordt genegeerd door
achter de naam een `/` te zetten.

```
# Windows image file caches
Thumbs.db
ehthumbs.db

# Folder config file
Desktop.ini

# Recycle Bin used on file shares
$RECYCLE.BIN/

# Windows Installer files
*.cab
*.msi
*.msm
*.msp
```

_Bron: [Windows.gitignore]_

### Git Extentions

Heeft hier een handigheidje voor. In het [git commit] scherm kan je met
`rechter muis knop -> Add file to .gitignore` interactief ignores toevoegen.

![rechter muis knop -> Add file to .gitignore][gitignore01-gitextensions]
![interactief ignores toevoegen][gitignore02-gitextensions]

## [git add](http://git-scm.com/docs/git-add)

_[git stage](http://git-scm.com/docs/git-stage) is een synoniem van dit commando_

__Voegt bestanden toe aan de index van de Git repository.__

### Git Extentions

Heeft deze functie in het [git commit] scherm.

`Stage` of `Stage all` in het [git commit] scherm.

![Stage of Stage all][add-gitextensions]

### Git Extentions

Heeft hier een handigheidje voor. In het [git commit] scherm kan je met
`rechter muis knop -> Add file to .gitignore` interactief ignores toevoegen.

![rechter muis knop -> Add file to .gitignore][gitignore01-gitextensions]
![interactief ignores toevoegen][gitignore02-gitextensions]

## [git branch](http://git-scm.com/docs/git-branch)

__Toont, creëert, of verwijdert branches.__

### Git Extentions

Heeft deze functie vanuit het hoofdscherm, hier staat een overzicht met alle
branches.

`rechter muis knop -> Create new branch` of `Delete branch`

![rechter muis knop -> Create new branch of Delete branch][branch-gitextensions]

# Git workflow

### Extra lees voer

[Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)  
[GitHub Flow](http://scottchacon.com/2011/08/31/github-flow.html)  
[A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)  

# voetnoten

## untracked bestanden

Bestanden binnen de Git repository map die nog niet met [git add] zijn
toegevoegd.

[git-scm.com]: http://git-scm.com/
[Git Extentions]: https://github.com/gitextensions/gitextensions
[init-gitextensions]: img/init-gitextensions.png
[commit-gitextensions]: img/commit-gitextensions.png
[untracked bestanden]: #untracked-bestanden
[Windows.gitignore]: https://github.com/github/gitignore/blob/master/Global/Windows.gitignore
[gitignore01-gitextensions]: img/gitignore01-gitextensions.png
[gitignore02-gitextensions]: img/gitignore02-gitextensions.png
[git commit]: #git-commit
[add-gitextensions]: img/add-gitextensions.png
[branch-gitextensions]: img/branch-gitextensions.png
