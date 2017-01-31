#GitHub, GitKraken, en terminal de commande [terminal, cmder, iterm (sous Mac)]
#Les équivalences sur les différents outils - Step by step

####Remarque : toutes les actions se font dans le dossier ou répertoire de travail concerné.

**Soyons vigilants** : les **noms** des **dossiers/répertoires** et des **fichiers** sont **tous** :
- en **MINUSCULES**
- **SANS** ESPACES
- **SANS* CARACTERES SPECIAUX (accents, #, &, =, ç...)
- **SAUF** **-** ou **_**.

---

###Ce fichier n'est pas finalisé, il à vocation à évoluer avec votre prise en main des différents outils (GitHub, GitKraken et bien évidemment la console (terminal, cmder, iterm...) 

---

###Feuille de route :

- [ ] lire l'ensemble du fichier
- [ ] créer un **nouveau** repository sur **son GitHub personnel** que l'on appelle _fantome_ [ATTENTION, on le créé avec son fichier _readme.md_ renseigné (par exemple "tester les commandes GitHub, GitKraken et en mode Terminal de commande") (avec le Terminal, cmder, iterm sous Mac...)]
- [ ] repérer et tester pour chaque action le(s) bouton(s) à cliquer / action(s) à effectuer sur les différents outils
- [ ] compléter le tableau avec le résultat de vos tests (si une action est possible avec un outil, noter les instructions/commandes/boutons à cliquer et _si ce n'est **pas possible** avec un outil..._ :imp:!)
- [ ] on ajoute bien évidemment des lignes au tableau si les commanes / instructions n'y sont pas encore
- [ ] dès qu'une tâche dans cette liste **est finie à _100%_**, ajouter un `x` entre les [ ] pour indiquer que c'est fait comme ci-dessous
- [x] c'est fait ! :sunglasses:

---

:imp: = non, travailler avec un autre outil... ahhh :alien:

:octocat: = à compléter par vos tests (c'est possible avec cet outil : indiquer les instructions à suivre, c'est impossible :imp:)

---

Actions | Terminal (ou cmder par ex.) | GitHub | GitKraken
--- | --- | --- | ---
**En local** aller sur le répertoire _raçine C://_ | cd../.. | :imp: | :imp:
**En local** rentrer dans le répertoire de travail `htdocs` de xampp | cd xampp\htdocs | :imp: | :imp:
Créer un _dossier_ | **mkdir** mondossier | :imp: | :imp:
_(Ré-)_ Initialiser le tracking d'un _dossier_ | **git init** | :imp: | :imp:
Créer un _fichier_ | **touch** monfichier.ext | bouton `create new file` | :octocat:
Voir les sous-dossiers | **ls** _qui est l'abbréviation anglaise de `list subfiles`_ | :octocat: | :octocat:
Voir les sous-dossiers **cachés** | **ls -a** | :octocat: | :octocat:
Vérifier l'état des dossiers et fichiers trakés avec git | git status | :octocat: | :octocat:
Cloner un _repository_ de GitHub pour travailler en local | **git clone** https://monrepo | :imp: | :octocat:
Ajouter _tous_ les fichiers _modifiés_ au tracking | __git add `*`__ ou **git add .** | :imp: | :octocat:
Ajouter _un_ fichier _modifié_ au tracking | **git add `monfichier.ext`** | :imp: | :octocat:
Enregistrer les modifications | **git commit -m "description"** | :octocat: | :octocat:
Raccourci de  _rajouter au traking_ et _enregistrer_ | **git commit -a -m "description"** | :octocat: | :octocat:
Récupérer sur son répertoire _local_ les derniers changement faits sur GitHub | **git pull origin `master` (OU `mabranche`)** | :octocat: | :octocat:
Récupérer sur son repository _GitHub_ les derniers changement faits en local | **git push origin `master` (OU `mabranche`)** | :octocat: | :octocat:
Créer une branche (distincte de la _master_) | **git branch `nomdemabranche`** | :octocat: | :octocat:
Passer de la branche _master_ à la branche _mabranche_ | **git checkout `mabranche`** | :octocat: | :octocat:
Passer de la branche _mabranche_ à la branche _master_ | **git checkout `master`** | :octocat: | :octocat:
