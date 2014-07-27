# Git 101

# Git?

> Git is een gratis en open-source gedistribueerd versie beheer systeem,
    ontworpen om kleine tot hele grote projecten te beheren met snelheid en
    efficiëntie.

> Git is makkelijk te leren, heeft weinig resources nodig en is super snel. Het
    presteert beter dan andere versie beheer systemen door de ondersteuning van
    lokaal branching, staging areas en meerdere workflows.

_Bron: [git-scm.com](http://git-scm.com/)_

Git heeft alleen een commandline interface, er zijn echter diverse tools die met
een grafische interface bovenop Git opereren.

# Git binnen Windows

[Git Extentions], is de meest complete GUI voor windows. Deze heeft bijna alle
Git commando's visueel beschikbaar, integreert met Windows Explorer en biedt een
extensie voor Visual Studio. In deze client staat de visuele weergave van een
Git repository centraal, vanuit deze weergave zijn alle mutaties te zien.

[Git Extentions]: https://github.com/gitextensions/gitextensions

## Aangeraden instellingen

* Git
* * Gebruik Putty voor SSH
* * Checkout Windows-style, commit Unix-style
* * git-cheetah en andere shell extension uitvinken, Git Extentions installeerd
zijn eigen.
* Git Extentions
* * Kies bij de eerste opstart voor de Engelse taal, hiermee verkom je dat de
git commando's vernederlandst worden weergegeven.

# Git commando's

## [git init](http://git-scm.com/docs/git-init)

Maakt een lege Git repository aan.

### Git Extentions

`rechter muis knop -> GitEx Create new repository...` op of in een map.

![rechter muis knop -> GitEx Create new repository...][init-gitextensions]

[init-gitextensions]: img/init-gitextensions.png

## [git commit](http://git-scm.com/docs/git-commit)

Legt veranderingen vast in de Git repository.

### Git Extentions

`rechter muis knop -> GitEx Commit...` op of in de Git repository map.

![rechter muis knop -> GitEx Commit...][commit-gitextensions]

[commit-gitextensions]: img/commit-gitextensions.png

## [gitignore](http://git-scm.com/docs/gitignore)

Specificeert te negeren [untracked bestanden](#untracked-bestanden).

### Git Extentions

`rechter muis knop -> GitEx Commit...` op of in de Git repository map.

![rechter muis knop -> GitEx Commit...][commit-gitextensions]

[commit-gitextensions]: img/commit-gitextensions.png

# voetnoten

## untracked bestanden

Bestanden binnen de Git repository directory die nog niet met
[git commit](#git-commit) zijn toegevoegd.
