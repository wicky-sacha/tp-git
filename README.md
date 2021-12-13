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

## Conflit simple

- [ ] Depuis le site Github (le dépôt "distant"), utiliser le bouton éditer ✏ pour cocher cette case. Avec "edit depuis Github", comme message de commit.
- [ ] Cochez cette case depuis VSCode (le dépot sur votre PC). Faire un commit "edit local"
- Demandez à VSCode de synchroniser.

# Branches


# "Ammend", Réordonner et "squash" les commits.

