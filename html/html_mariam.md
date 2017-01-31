##Mes premiers pas html 

Un document HTML est un document au format TEXTE (ASCII) et peut être créé par n'importe quel éditeur.

##Mon premier document

##Titres 

```
<h1>Titre h1</h1>
<h2>Titre h2</h2>
<h3>Titre h3</h3>
<h4>Titre h4</h4>
<h5>Titre h5</h5>
<h6>Titre h6</h6>
```

###Corps de la page

```
<p>Ceci est un pargarphe/p>

<p>Casi tres millones de estudiantes universitarios de 33 países europeos han participado en el popular programa de becas de estudios que, según Bruselas, es un instrumento “clave” para impulsar la movilidad laboral y combatir el alto desempleo juvenil. España es el país que más estudiantes exporta a Europa, más de 30.000, y también es el que recibe más becados, por delante de Francia, Reino Unido, Alemania e Italia. Sin embargo, también es el que registra la mayor tasa2 de paro juvenil de la Unión Europea, un dramático 48,5% frente al 22% de la media europea. Entonces, ¿el programa Erasmus es realmente una garantía para encontrar trabajo?</p>
```
```
<!-- Paragraphes pré-formatés -->
```
```
</pre>
Casi tres millones de estudiantes universitarios de 33 países europeos han participado en el popular programa de becas de estudios que, según Bruselas, es un instrumento “clave” para impulsar la movilidad laboral y combatir el alto desempleo juvenil. España es el país que más estudiantes exporta a Europa, más de 30.000, y también es el que recibe más becados, por delante de Francia, Reino Unido, Alemania e Italia. Sin embargo, también es el que registra la mayor tasa2 de paro juvenil de la Unión Europea, un dramático 48,5% frente al 22% de la media europea. Entonces, ¿el programa Erasmus es realmente una garantía para encontrar trabajo?
</pre>
```
```
<p> Voici la structure de base d'une page d'un page !DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Ma belle page</title>
  </head>
  <body>

  </body>
</html>
</p>
```
```
</-- pour faire des commentaire et expliquer son code-->
<p>Un paragraphe est un bloc de texte
  <p> Un pargraphe ne comprend pas les retours à la ligne.<br />
    Mais avec ma balise "<br />" je gère mes retours à la ligne !</p>
```

```
  <!-- La disposition du texte  -->
  <p style="text-align:right">Ce paragraphe sur deux est disposé à droite <br />
  <p style="text-align:center">Ce paragraphe sur deux est disposé au centre <br />
  <p style="text-align:left">Ce paragraphe sur deux est disposé à gauche <br />
```
```
  <p>Quel est le rôle de la balise HR?</p>
  <hr /hr>
  <p>Elle insère une ligne séparatrice dans le contenu de page html.<br /> Elle est auto-fermante(ou orpheline)... à ,e pas confondre avec la balise BR qui elle permet d'effectuer <br /> un retour à la ligne !<p>
```
```
<!-- La mise en valeur -->
<!-- STRONG -->
<p>Bonjour, ceci est montes en HTML alors <STRONG>soyez indulents</STRONG> s'il vous !</p>
<p>Bonjour, ceci est montes en HTML alors <em>soyez indulents</em> s'il vous !</p>
<p>Bonjour, ceci est montes en HTML alors <mark>soyez indulents</mark> s'il vous !</p>
```
```
<!-- Les listes -->
<!-- non-ordonnées (a puces) -->
<ul>
<li>Chat</li>
<li>Chien</li>
<li>Cheval</li>
</ul>
```
```
<!-- non-ordonnées (numérotées) -->
<ol>
<li>Pomme</li>
<li>Poire</li>
<li>Abricot</li>
</ol>
```
```
<!-- La couleur de fond -->
<p style="background-color:cyan">Casi tres millones de estudiantes universitarios de 33 países europeos han participado en el popular programa de becas de estudios que, según Bruselas, es un instrumento “clave” para impulsar la movilidad laboral y combatir el alto desempleo juvenil. España es el país que más estudiantes exporta a Europa, más de 30.000, y también es el que recibe más becados, por delante de Francia, Reino Unido, Alemania e Italia. Sin embargo, también es el que registra la mayor tasa2 de paro juvenil de la Unión Europea, un dramático 48,5% frente al 22% de la media europea. Entonces, ¿el programa Erasmus es realmente una garantía para encontrar trabajo?</p>
<p style="background-color:black; color:white">Casi tres millones de estudiantes universitarios de 33 países europeos han participado en el popular programa de becas de estudios que, según Bruselas, es un instrumento “clave” para impulsar la movilidad laboral y combatir el alto desempleo juvenil. España es el país que más estudiantes exporta a Europa, más de 30.000, y también es el que recibe más becados, por delante de Francia, Reino Unido, Alemania e Italia. Sin embargo, también es el que registra la mayor tasa2 de paro juvenil de la Unión Europea, un dramático 48,5% frente al 22% de la media europea. Entonces, ¿el programa Erasmus es realmente una garantía para encontrar trabajo?</p>
```

##Les couleurs 
```
<p style="color: crimson">H</p>
<p style="color: lightseagreen">T</p>
<p style="color: darkgreen">M</p>
<p style="color: teal">L</p>
  <br />
<p style="color: #FF0000">H</p>
<p style="color: #FFFF00">T</p>
<p style="color: #800000">M</p>
<p style="color: #800000">L</p>
  <br />
 ```
 
##Les Liens 
 ```

  <!-- Le navigateur va aller charger le fichier.css -->
  <link rel="stylesheet" type="text/css" href="style.css" />
  <a href="http://www.lbpa-france.com/">Mon lien</a>
```

##Les images 
```
  
  <img src="../img" />
<img src="../img/logo_html.png" />
```

