[CSS](#CSS)
	

**Travail collaboratif:  Languages informatiques**

**Définition**

**Informations sur les langages**

**Quand peut-on les utiliser ?**
 


**CSS**
	
	<a name="CSS"/>
![CSS](http://www.myiconfinder.com/uploads/iconsets/256-256-8b61de4c84033266e15317a6eb9fda2d-css3.png)

**Définition:**
CSS est l'acronyme de Cascading Style Sheet, ou feuille de style en cascade en français. 
Le CSS permet d'insérer des styles sur un code HTML ou XHTMl et donc permet de définir très précisément le comportement 
de chaque élément de la page.Une bonne pratique de développement consiste à débarrasser le coe HTML5 de toute information de mi
se en forme et de laisser les feuilles de styles  (CSS donc) se charger de ce travail. 
Ainsi, le fond est bien séparé de la forme, simplifie le travail à l'utilisateur et lui permet de créer un ste internet optimal.

**Quand et comment l'utiliser ?**

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




