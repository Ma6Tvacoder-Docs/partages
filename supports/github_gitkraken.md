#GitHub, GitKraken, en terminal de commande [terminal, cmder, iterm (sous Mac)]
#Les équivalences sur les différents outils - Step by step

####Remarque : toutes les actions se font dans le dossier ou répertoire de travail concerné.

**Soyons vigilants** : les **noms** des **dossiers/répertoires** et des **fichiers** sont **tous** :
- en **MINUSCULES**
- **SANS** ESPACES
- **SANS** CARACTERES SPECIAUX (accents, #, &, =, ç...)
- **SAUF** **-** ou **_**.

---

###Ce fichier n'est pas finalisé, il à vocation à évoluer avec votre prise en main des différents outils (GitHub, GitKraken et bien évidemment la console (terminal, cmder, iterm...) 
###Son évolution s'enrichit des expériences de chacun... Alors contribuez TOUS ... eh oui ce qui ne marche pas :scream: est aussi utile à savoir pour utiliser le meilleur outil :sunglasses: !

---

###Feuille de route :

- [x] lire **_l'ensemble_** du fichier, ...puis...
- [x] créer un **nouveau** repository sur **son GitHub personnel** que l'on appelle _fantome_ [ATTENTION, on le créé avec son fichier _readme.md_ renseigné (par exemple "tester les commandes GitHub, GitKraken et en mode Terminal de commande")
- [x] repérer et tester pour **chaque ACTION** indiquée dans le tableau le(s) bouton(s) à cliquer ou instructions en ligne de commande à taper / action(s) à effectuer sur les différents outils
- [x] compléter le tableau avec le résultat de vos tests (si une action est possible avec un outil, noter les instructions/commandes/boutons à cliquer et _si ce n'est **pas possible** avec un outil..._ :imp:!)
- [x] on ajoute bien évidemment des lignes au tableau si les commandes / instructions n'y sont pas encore, mais que vous avez **trouvées _(après recherche **sérieuse** sur internet)_ ET testées"" !!
- [ ] les utilisateurs de Macs sont invités à noter/demander les différences dans la dernière colonne... il y en à parfois...:sweat:
- [x] dès qu'une tâche dans cette liste **est finie à _100%_**, ajouter un `x` (en mode EDIT) entre les [ ] pour indiquer que c'est fait comme ci-dessous
- [x] c'est fait ! :sunglasses:

---

:imp: = non, travailler avec un autre outil... ahhh :alien:

:octocat: = à compléter par vos tests (c'est possible avec cet outil : indiquer les instructions à suivre, c'est impossible :imp:)

---

Actions | Terminal (ou cmder par ex.) | GitHub | GitKraken | Sous Mac (Terminal ou iterm)
--- | --- | --- | --- | ---
**En local** aller sur le répertoire _raçine C://_ | cd../.. | :imp: | :imp: | cd.. ne fonctionne PAS aussi => indiquer **cd/tous/les/répertoires à parcourir** à CHAQUE instruction **cd/XXX**
**En local** rentrer dans le répertoire de travail `htdocs` de xampp | cd xampp\htdocs | :imp: | | :octocat: | cd /Applications/xampp/htdocs
Vérifier le répertoire en cours d'utilisation **sous MAC ou autre** | **pwd** | **pwd** | **pwd** | **pwd** pour Present Writing Directory
Créer un _dossier_ | **mkdir** mondossier | :imp: | :imp: | :octocat:
_(Ré-)_ Initialiser le tracking d'un _dossier_ | **git init** | :imp: | Aller dans Fichiers > Init Repo > Choisir le dossier que l'on veut tracker | :octocat:
Créer un _fichier_ | **touch** monfichier.ext | bouton `create new file` | :octocat: | :octocat: | :octocat:
Voir les sous-dossiers | **ls** _qui est l'abbréviation anglaise de `list subfiles`_ | :imp: | :imp: | :octocat:
Voir les sous-dossiers **cachés** | **ls -a** | :imp: | :imp: | :octocat:
Vérifier l'état des dossiers et fichiers trakés avec git | **git status** | Actualiser la page en cliquer sur le bouton actualiser ou en appuyant F5  | Aller dans Fichiers > Check for Updates  | :octocat:
Cloner un _repository_ de GitHub pour travailler en local | **git clone** https://monrepo | :imp: | Aller dans Fichiers > Clone Repo Choisir un dossier ou l'on veut cloner et mettre l'url du repository | :octocat:
Ajouter _tous_ les fichiers _modifiés_ au tracking | __git add `*`__ ou **git add .** | :imp: | :octocat: | :octocat:
Ajouter _un_ fichier _modifié_ au tracking | **git add `monfichier.ext`** | :imp: | :octocat: | :octocat:
Enregistrer les modifications | **git commit -m "description"** | :octocat: | Clique droit sur le fichier que l'on veut modifier  > Eddit Commit puis modifier les commentaires et ensuite cliquer sur Update Message | :octocat:
Raccourci de  _rajouter au traking_ et _enregistrer_ | **git commit -a -m "description"** | :octocat: | :octocat: | :octocat:
Récupérer sur son répertoire _local_ les derniers changement faits sur GitHub | **git pull origin `master` (OU `mabranche`)** | :octocat: | Sur la fenetre d'affichage principale cliquer sur **Pull** | :octocat:
Récupérer sur son repository _GitHub_ les derniers changement faits en local | **git push origin `master` (OU `mabranche`)** | :octocat: | Sur la fenetre d'affichage principal cliquer sur **Push** | :octocat:
Créer une branche (distincte de la _master_) | **git branch `nomdemabranche`** | Une fois dans le dossier ou l'on veut creer une branche on clique sur le bouton **"Branch: master"** puis on entre un nom de branche et on clique sur **"Create"**| Sur la fentre d'affichage principale cliquer sur "Branch" puis entrer un nom et valider | :octocat:
Passer de la branche _master_ à la branche _mabranche_ | **git checkout `mabranche`** | On clique sur **"Branch"** puis automatiquement sa affichera les branches créer et on a plus qu'a choisir dans laquelle on veut se mettre. | Clique droit sur la branche **"master"** >  Checkout Master. | :octocat:
Passer de la branche _mabranche_ à la branche _master_ | **git checkout `master`** | Voir ci-dessus | Clique droit sur la branche **"nom de votre branche"** > Checkout **"nom de votre branche"**. | :octocat:
