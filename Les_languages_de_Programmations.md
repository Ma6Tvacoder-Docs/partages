# Les Langages de Programmation


## Navigation

##### [CakePhp](#PHPwiki)
##### [Symfony](#S3)
##### [CSS](#CSS)
##### [JavaScript](#Exemple)
##### [Node JS](#Node JS)
##### [Ajax JS](#AjaxJs)
##### [Jquery](#jLink)

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

<a name="S3"/>
![alt text](https://www.eewee.fr/wp-content/uploads/2014/03/logo-symfony-2-763x362.jpg)

## Framework Symfony 3

- Symphony est un langage de programmation écrit en PHP fondé en 2005 par l'agence web SensioLabs, ce langage permet d'avoir une facilitée et une rapiditée dans le developpement d'un site web car il utilise des fonctionnalités modulables et adaptables.

- Le site DailyMotion par exemeple a été programmé sous la forme Symfony. 

- Voici un exemple de codage.

![alt text](http://twimgs.com/ddj/images/article/2012/0912/Symfony.gif)

### CSS

<a name="CSS"/>
![CSS](http://www.myiconfinder.com/uploads/iconsets/256-256-8b61de4c84033266e15317a6eb9fda2d-css3.png)

#### Définition:
CSS est l'acronyme de Cascading Style Sheet, ou feuille de style en cascade en français. 
Le CSS permet d'insérer des styles sur un code HTML ou XHTMl et donc permet de définir très précisément le comportement 
de chaque élément de la page.Une bonne pratique de développement consiste à débarrasser le coe HTML5 de toute information de mi
se en forme et de laisser les feuilles de styles  (CSS donc) se charger de ce travail. 
Ainsi, le fond est bien séparé de la forme, simplifie le travail à l'utilisateur et lui permet de créer un ste internet optimal.

#### Quand et comment l'utiliser ?

 C'est lui qui vous permet de choisir la couleur de votre texte.
Lui qui vous permet de sélectionner la police utilisée sur votre site.
Lui encore qui permet de définir la taille du texte, les bordures, le fond…
Et aussi, c'est lui qui permet de faire la mise en page de votre site.
Vous pourrez dire : je veux que mon menu soit à gauche et occupe telle largeur, 
que l'en-tête de mon site soit calé en haut et qu'il soit toujours visible, etc.

```CSS
html, body {
 margin: 0;
 padding: 0;
 }
body {
 background-color: white; 
 font-family: Verdana, sans-serif; 
 font-size: 100%;
 }
h1 {
 font-size: 200%; 
 color: navy; 
 text-align: center;
 }
h2 {
 font-size: 150%; 
 color: red; 
 padding-left: 15px;
 }
p,ul,li,td {
 color: black; 
 }
a:link {
 color: green;
 text-decoration: underline;
 }
a:visited {
 color: gray;
 }
a:hover {
 color: red;
 text-decoration: none;
}
a:active, a:focus {
 color: red;
}
```


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
<a name=”jlink”/>
![Jquery](http://static.crazyws.fr/resources/blog/2012/06/jquery-18.png)
## le Jquery est une bibliothèque javascript libre !
### informations
+ parcours et modification du DOM ( interface de programation )
+ évenements ( slide d'images , caroussel , interactions )
+ effets visuels et animations
+ manipulations des feuilles de style en cascade (ajout/suppression des classes, d'attributs…)
+ Ajax ( Asynchronous JAvascript and Xml)
+ création de plugins
+ création d'utilitaires

### Ses Utilisations
+ Vérifier si un élément contient une certaine classe
+ Ajouter ou enlever une classe
+ Utilisation d'une fonction spécifique à Internet Explorer
+ Lier une fonction à un événement
+ Ajouter du contenu à un élément HTML
+ Préchargement d'images
+ Valider si un option est sélectionné
+ Cacher un élément HTML
+ Détection de navigateur avec jQuery
+ Valider si un élément existe
+ Cacher ou fermer automatiquement un élément après un certain temps
+ Obtenir l'élément parent le plus près

### exemple de bout de code Jquery

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
$(document).ready(function() {                    // Lorsque le document est chargé
    $(".load_page_on_click").click(function() {   // Lorsque l’on clique sur un élément d'attribut class "load_page_on_click"
        var email = $("input[name=email]").val(); // Variable contenant la valeur d'un élément input d'attribut name "email"
        $.ajax({                         // Exécution d’une requête Ajax avec la configuration donnée par l'objet suivant :
            async: "true",               // - requête asynchrone
            type: "GET",                 // - type HTTP GET
            url: "mapage.php",           // - URL de la page à charger
            data: "email=" + encodeURIComponent(email) + "&action=get_email", // - données à envoyer
            error: function(errorData) { // - fonction de rappel en cas d’erreur
                $("#error").html(errorData);
            },
            success: function(data) {    // - fonction de rappel pour le traitement des données reçues en cas de succès
                $("#container").html(data); $("#error").append("Contenu chargé");
            }
        }); // Fermeture de l'appel à la fonction $.ajax
    });     // Fermeture de la fonction de rappel du $(".load_page_on_click").click
});         // Fermeture de la fonction de rappel du $(document).ready
```

ceci était un exemple d'ajax en Jquery

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



![image](http://alibolori.ir/Biography/wp-content/uploads/2016/01/html.jpg)


Le HTML (« HyperText Mark-Up Language ») est un langage dit de « marquage » (de « structuration » ou de « balisage »)
dont le rôle est de formaliser l'écriture d'un document avec des balises de formatage.
Les balises permettent d'indiquer la façon dont doit être présenté le document et les liens qu'il établit avec d'autres documents. 
Les éléments du langage

Les spécifications HTML font la différence entre les types d'éléments et les balises (ou marqueurs). 

#l'élément page HTML et ses balises.

Les signes < et > délimitent la balise. Ici <html> est une balise d'ouverture et </html> une balise de fermeture.
L'élément HTML est, quant à lui, encadré par une balise d'ouverture de l'élément HTML <html> et une balise de fermeture de l'élément HTML 
</html> contenant elle aussi le nom de l'élément et précédée par un slash (/) spécifiant la balise comme une balise de fermeture. La balise d'ouverture peut avoir divers attributs lui étant incorporé si nécessaire.

Attention, les éléments ou textes contenus entre ces deux balises sont considérés comme le contenu de l'élément HTML 
(ici le contenu de la page Web). On peut faire le même raisonnement avec tout type d'élément du langage, 
hormis le fait que certains éléments ne possèdent pas de contenu et ne possèdent pas de balises de fermeture, ce
sont les balises orphelines (voir tableau 1 : les éléments).
Une autre notion importante de HTML est qu'il est basé sur la technique de l'hypertexte, cette technique permet de spécifier des URL au sein d'une même page ou entre des pages différentes. Si l'on prend la globalité des liens existant sur Internet on aurait un aperçu de ce qu'est le World Wide Web, une gigantesque toile sur laquelle des noeuds sont en fait des serveurs de contenus multimédias et les centaines de fils composants la toile les câbles reliant les machines au réseau.
<html>
	<head>
		<title>Titre affiché dans la barre du navigateur</title>
	</head>
	
	<body>
		<h1>titre de niveau 1</h1>
		<h2>titre de niveau 2</h2>
		<h2>titre de niveau 3</h2>
		<p>paragraphe 1</p>
		<p>paragraphe 2</p>
		<p>paragraphe 3</p>
		<ul>
			<li>item 1</li>
			<li>item 2</li>
			<li>item 3</li>
		</ul>
	</body>
</html>
