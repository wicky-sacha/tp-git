# Suivre les consignes de ce document

Faire les nodifications indiquées directement dans ce même document en suivant les indications.

## Faire un fokr de ce dépôt

Depuis la page Github de ce dépôt, faire un fork de ce même dépôt.

Puis cloner votre fork sur votre PC (avec VSCode).

- [X] Chochez cette checkbox en plaçant un "**X**" entre les deux `[ ]` en début de ligne.
- Faire un commit avec le message "test commit et push"
- Faire un push du commit sur Github.

## Principe du TP

- [X] Chochez les checkbox quand demandé et/ou répondez directement dans ce document.
- Suivre les indications sur les commits et autres manipulation.

L'historique git de vos commits sera la preuve que vous avez fait le TP.

# Gitignore

Le fichier `.gitignore` sert à indiquer à Git les fichiers qu'il doit ignorer (c-à-d qu'il ne gardera pas l'historique de leurs modifications).

## génération automatique du fichier `.gitignore`

- Installez l'extension _".gitignore Generator"_ .
- L'utiliser (`Shift+CMD+P` Generate .gitignore File).
  - Faire un fichier `.gitignore` en sélectionnant :
    - [X] windows
    - [X] macos
    - [X] visualstudiocode
- [X] cocher et faire commit "ajout .gitignore"

## ajout manuel à `.gitignore`

- Faire un fichier `/public/video/a-ignorer.txt`
- Ajouter en fin de fichier `.gitignore` la ligne suivante :
  - `/public/video`
- [X] cocher et commit "ajout dossier à .gitignore"
- Synchroniser les commit avec Github
  - constater que le fichier `/public/video/a-ignorer.txt` n'a pas été publié surGithub

# Conflits

- [X] Depuis le site Github (le dépôt "distant"), utiliser le bouton éditer ✏ pour cocher cette case. Avec "edit depuis Github", comme message de commit.
- [X] Cochez cette case depuis VSCode (le dépot sur votre PC). Faire un commit "edit local"
- Demandez à VSCode de synchroniser.
  - Cela doit echouer.
  - Faire `Shift+CMD+P` Git: Pull (rebase)
    - Dans ce cas faire "accept both change" et éditer pour garder les deux cases cochées.
    - Valider le changement du commit
    - Finir "rebase".
- Faire un "push" vers Github.

# Branches

## Faire une branche

- Faire une branche en cliquant en bas-à-gauche sur VSCode ; la nommer (en adaptant) _"votre-pseudo/test-branche"_
  - VSCode vous place automatiquement dans la nouvelle branche.
- [ ] Cochez et commit : "1re commit dans branche"
- [ ] Puis cochez et commit "2nd commit dans branche"
- Regardez la liste des commits dans le volet Chronologie en bas de l'exlporateur de VSCode

## Changer de branche

- Retourner à la branche _"master"_ avec le bouton en bas à droite
  - Regardez les deux checkboxs audessu, elle ne son pas cochées (**important:** les laissez ainsi) .
  - [X] Cochez et commit : "commit dans master à rebaser dans branche"
- Regardez la liste des commits
  - Vous ne voyez pas les commits fait dans la branche
- Retourner à la branche  _"????/test-branche"_

## "Rebaser" une branche

- Utiliser la commande `Shift+CMD+P` _Git rebaser la branche"
  - Choisir la branche "Master"
  - Accpeter la version courante dans l'éditeur
  - Valider la resolution de conflit dans le volet "Changements rebase" du panneau "Contrôle de code source"

## "Merger" une branche

- Retourner à la branche "Master"

# "Ammend", Réordonner et "squash" les commits.


# Archive d'un dépôt

Archive d'un dépôt local : [git archive](https://git-scm.com/docs/git-archive).