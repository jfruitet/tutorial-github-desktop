Mon GitHub Desktop pas à pas
==================

J’ai beaucoup de mal à me repérer dans l’utilisation de Git.

A plusieurs reprises j’ai perdu des « workspace » suite à des erreurs de manie, surtout sur Mac donc le système de fichier ne m’est pads familier…

## Installer l’interface
*Il faut installer Git en premier sur la machine.
*Puis aller sur GitHub et cliquer sur *Clone on Desktop*
Une application **GitHub Desktop App** s’installe dans le dossier *Applications*


# Ou suis-je
Première difficulté, déterminer où tutoriel est installé…

Le tutoriel est géré par **GitHub Desktop App** sous le nom de repository local *username/tutorial-github-desktop*

## Que dois-je faire ?
* Commencer par créer une nouvelle branche…
A priori la branche initiale s’appelle master

On peut alors visualiser le contenu de la branche (*View branch*)

* Y modifier des données, par exemple le fichier README.md avec un  éditeur de texte comme TextEdit.
* **Commiter** la modification en remplissant un descriptif

Au fur et à mesure des évolutions du texte celles-ci sont-elles prises en compte ?

Oui si le contenu de l’éditeur est enregistré… et que le document modifié soit **commité**.

* Et maintenant ?

## Pull request ou Publish ou Synchronise ?
### Pull request
Permet d’adresser une demande de révision au propriétaire du GitHub.

Quand la révision est acceptée, celui-ci peut fusionner les branches avec la branche maîtresse. 

Cela se fait depuis le GitHub en ligne.

### Publish
Cela consiste à publier le Repository Git local vers GitHub.


Un nouveau repository est créée sur le GitHub, lequel peut ensuite se synchroniser avec le repository local.

### Sync
Quand un repository distant sous GitHub est créé, les modification locales peuvent être **synchronisées** avec celui-ci. La synchronisation porte sur la branche active.

Il faudra faire une demande **Pull request** pour que la fusion avec la branche master soit effective.

