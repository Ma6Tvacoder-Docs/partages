# Les Langages de Programmation

## Navigation

[php](#PHPwiki)
[JavaScript](#Exemple)
[Node JS](#Node JS)
[Ajax JS](#AjaxJs)

## Les langages

<a name="PHPwiki"/>
### CakePHP

#### Définition

* **CakePHP** est un *framework* (ensemble cohérent de composants logiciels structurels qui servent a créer les fondations et les grandes lignes d'un lociel) web libre écrit en *PHP* distribué sous licence *MIT* .   

#### Information sur le languages

* **Cake** facilite l'utilisation de *Bases de données* avec *active record* qui est une approche pour lire les données d'une base.
Il encourage également fortement l'utilisation de l'architecture *Modèle-Vue-Contrôleur* qui est un motif d'architecture logicielle destiné au interfaces graphiques(tres populaire pour les applications web).
*Cakephp* est compatible avec PHP5 et PHP7 , il sert également a avoir des composants de sécurité de gestion des droits et de gestion des sessions et caché des vues et des actions flexible.

#### quand peut-on l'utiliser#

* On peut utiliser *cake* pour l'utilisation de CRUD(create,read,update,delete) afin de simplifiée l'utilisation des bases de données SQL , pour dispatché l'url permettant d'obtenir des adresses aisément lisibles , validations de données  et pour avoir un script en ligne de commande permettant la génération automatique de code a partir du modele physique de données.

<a name=”Exemple”/>
### Javascript

![JS](http://makemedev.com/content/images/2016/10/javascript.jpg)
JavaScipt est un langage de programmation Web qui rend n'importe quelle page morose en une vraie machine dynamique! Il permet de créer un site interactif et attrayant.
Créé dans les années 90 il est désormais un des poids lourds du développement Web.
Le JavaScript est un langage informatique utilisé sur les pages web. 
Ce langage à la particularité de s'activer sur le poste client, en d'autres mots c'est votre ordinateur qui va recevoir le code et qui 
devra l'exécuter. C'est en opposition à d'autres langages qui sont activé côté serveur.
L'exécution du code est effectué par votre navigateur internet tel que Firefox, Chrome ou Internet Explorer.

L'une des choses primordiale à savoir est de bien se rendre compte que le JavaScript n'a aucun rapport avec le Java qui est un autre langage informatique.

La particularité du JavaScript consiste à créer des petits scripts sur une page HTML dans le but d'ajouter une petite animation ou un effet
particulier sur la page. Cela permet en général d'améliorer l'ergonomie ou l'interface utilisateur, mais certains scripts sont peu utile
et servent surtout à ajouter un effet esthétique à la page. 

#### Voici quelques exemples de ce qui est réalisable grâce au JavaScript :

- Un système de chat, comme celui de Facebook.
- Une suggestion lors de la frappe dans un champ de texte, comme lors d'une recherche avec Google. 
- Un lecteur de vidéos ou de musiques, aussi puissant que celui de Youtube. 
- Des jeux. 
- La modélisation 3D d'une Lamborghini affichée grâce à l'API WebGL et à la bibliothèque Three.js 
Et bien d'autres choses !

```javascript
 function changeCouleur(nouvelleCouleur) {
   elem = document.getElementById("para1");
   elem.style.color = nouvelleCouleur;
 }
```

<a name="Node JS"/>
### NodeJS

#### Definition

![Node JS](https://nodejs.org/static/images/logo.svg "Node JS")


Node.js est une plateforme construite sur le JavaScript runtime de Chrome pour facilement construire un réseau d’applications rapide et
évolutif. Node.js utilise un modèle événementiel, sans blocage I/O qui le rend léger et efficace, parfait pour des applications en temps
réel avec un volume de données important qui fonctionne sur les appareils distribués

Node.js est une plateforme de développement Javascript,


#### Informations sur NodeJS

Node.js est une plateforme logicielle libre et événementielle en JavaScript orientée vers les applications réseau qui doivent pouvoir 
monter en charge.
Elle utilise la machine virtuelle V8 et implémente sous licence MIT les spécifications CommonJS.
Node.js contient une bibliothèque de serveur HTTP intégrée, ce qui rend possible de faire tourner un serveur web sans avoir besoin d'un
logiciel externe comme Apache ou lighttpd, et permettant de mieux contrôler la façon dont le serveur web fonctionne.
Concrètement, node.js est un environnement d'assez bas niveau permettant d'exécuter du JavaScript non plus dans le navigateur web mais
sur le serveur.
Node.js est de plus en plus populaire comme plateforme serveur, elle est utilisée par Groupon, SAP, LinkedIn,Microsoft,Yahoo,Walmart,
Rakuten et PayPal.


### Quand peut-on utiliser Node JS

Node.js facilitent le travail de création d’applications événementielles, il permet d'utiliser le language JavaScript sur le serveur en
dehors du navigateur,avec des bibliothèques permettant de réaliser des actions comme écrire sur la sortie standard, ouvrir/fermer des
connections réseau ou encore créer un fichier.


### Exemple avec Hello World

```
const http = require('http');

const hostname = '127.0.0.1';
const port = 3000;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello World\n');
});

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`);
});

```
<a name="AjaxJs"/>
## AJAX JS

![alt text](http://tutos-django.com/uploads/ajax.png "Logo AjaxJs")

Asynchronous Javascript And XML ou plus simplement AJAX, n'est pas à proprement parler un langage de programmation mais plutôt 
un moyen d'en utiliser plusieurs conjointement.

Il fonctionne en utilisant JavaScript en arrière plan pour communiquer avec le serveur et permettre la mise à jour de la page 
(envoi/réception d'information) en temps réel sans actualisation de la page.

On retrouve notamment ce langage dans 
* l'interface de Gmail 
* Google Talk 
* ou sur Facebook pour gérer les photos et le chat.


### Exemple de script:

```javascript
<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="UTF-8">
    <title></title>
    <link rel="stylesheet" media="screen" href="style.css">
    <script src="http://code.jquery.com/jquery-1.6.2.min.js"></script> <!-- Les sources de la bibliothèque JQuery -->
    <script src="script.js"></script> <!-- La source qui contient le code d'envoi en Ajax -->
  </head>
  <body>
    <form method="post" action="add.php"> <!-- Formulaire envoyé par la méthode POST -->
      <fieldset>
	<legend>Choisissez deux nombres entiers</legend>
	<p><label>a = <input name="a" type="number" required></label></p> <!-- Premier nombre -->
	<p><label>b = <input name="b" type="number" required></label></p> <!-- Deuxième nombre -->
      </fieldset>
      <fieldset>
	<legend>R&eacute;sultat</legend>
	<p id="result"></p> <!-- Le résultat sera placé ici -->
      </fieldset>
      <p><button>Soumettre</button></p> <!-- Bouton de soumission -->
    </form>
  </body>
</html>
