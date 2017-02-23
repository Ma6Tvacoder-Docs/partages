<a name="PHPwiki"/>
[php](#PHPwiki)

#Définition#

* **CakePHP** est un *framework* (ensemble cohérent de composants logiciels structurels qui servent a créer les fondations et les grandes lignes d'un lociel) web libre écrit en *PHP* distribué sous licence *MIT* .   

#Information sur le languages#

* **Cake** facilite l'utilisation de *Bases de données* avec *active record* qui est une approche pour lire les données d'une base.
Il encourage également fortement l'utilisation de l'architecture *Modèle-Vue-Contrôleur* qui est un motif d'architecture logicielle destiné au interfaces graphiques(tres populaire pour les applications web).
*Cakephp* est compatible avec PHP5 et PHP7 , il sert également a avoir des composants de sécurité de gestion des droits et de gestion des sessions et caché des vues et des actions flexible.

* **Fonction**
1. Une fonction qui permet de rechercher et de remplacer des mots dans une variable.
2. Une fonction qui envoie un fichier sur un serveur.
3. Une fonction qui permet de créer des images miniatures (aussi appeléesthumbnails).
4. Une fonction qui envoie un mail avec PHP (très pratique pour faire une newsletter !).
5. Une fonction qui permet de modifier des images, y écrire du texte, tracer des lignes, des rectangles, etc.
6. Une fonction qui crypte des mots de passe.
7. Une fonction qui renvoie l'heure, la date…

#quand peut-on l'utiliser#

* On peut utiliser *cake* pour l'utilisation de CRUD(create,read,update,delete) afin de simplifiée l'utilisation des bases de données SQL , pour dispatché l'url permettant d'obtenir des adresses aisément lisibles , validations de données  et pour avoir un script en ligne de commande permettant la génération automatique de code a partir du modele physique de données.

```Cakephp 
function Nom_De_La_Fonction(argument1, argument2, ...) {
   liste d'instructions
```

```<?
$chaine = "Nombre de camions : ";

function ajoute_camion($mode='')
{

 global $chaine;

 static $nb=0;

  $nb++; // on incrémente le nombre de camions
 if($mode == "affiche"){
  echo $chaine.$nb; // on affiche le nombre de camions
 }
}

ajoute_camion(); // nb == 1
ajoute_camion(); // nb == 2
ajoute_camion(); // nb == 3
ajoute_camion("affiche"); // affiche Nombre de camions : 4
?>```

```$heure = date("H\hi");
print("<center><font size=\"2\" face=\"Arial\"> et celui en PHP. Il est $heure.</font></center>");```

```&lt?
function dire_texte($qui, $texte = 'Bonjour')
{
  if(empty($qui)){ // $qui est vide, on retourne faux
  return false;
  }else{
  echo "$texte $qui"; // on affiche le texte
  return true; // fonction exécutée avec succès
 }```
