#Les équivalences sur les différents outils - Step by step

####Remarque : toutes les actions se font dans le dossier ou répertoire de travail concerné.

:imp: = non

:octocat: = à compléter

---

Actions | Terminal (ou cmder par ex.) | GitHub | GitKraken
--- | --- | --- | ---
Créer un _dossier_ | **mkdir** mondossier | :imp: | :imp:
_(Ré-)_ Initialiser le tracking d'un _dossier_ | **git init** | :imp: | :imp:
Créer un _fichier_ | **touch** monfichier.ext | bouton `create new file` | :octocat:
Cloner un _repository_ de GitHub | **git clone** https://monrepo | :imp: | :octocat:
Ajouter _tous_ les fichiers _modifiés_ au tracking | __git add `*`__ ou **git add .** | :imp: | :octocat:
Enregistrer les modifications | **git commit -m "description"** | :octocat: | :octocat:
Récupérer sur son répertoire _local_ les derniers changement faits sur GitHub | **git pull origin `master` /OU/ `mabranch`** | :octocat: | :octocat:
Récupérer sur son repository _GitHub_ les derniers changement faits en local | **git push origin `master` /OU/ `mabranch`** | :octocat: | :octocat:
Créer une branche (distincte de la _master_) | **git branch `nomdemabranche`** | :octocat: | :octocat:
Passer de la branche _master_ à la branche _mabranche_ | **git checkout `mabranche`** | :octocat: | :octocat:
