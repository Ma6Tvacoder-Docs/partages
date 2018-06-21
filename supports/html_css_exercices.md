# Sommaire

## Principes de base

- On travaile **_toujours_** dans un répertoire __raçine__ qui se nomme **htdocs/**, **_et_** qui se situe dans votre **explorateur de fichiers** ici : _c/:xampp

[Exercice 1](#exo01)

[Exercice 2](#exo02)

[Exercice 3](#exo03)

[Exercice 4](#exo04)

---

<a name="exo01">

### Exo 1

Produire un document en html de ce que vous avez compris sur le cours de la journée d'hier sur l'introduction au langage HTML :
- qu’est-ce que le html, 
- ce que vous en déduisez et ce que vous comprenez de son fonctionnement. 

##### Pour cela :
1. créer un répertoire EXOS dans votre dossier en local HTML-CSS.

2. effectuer une mise à jour (ou MAJ) en ligne sur votre répertoire GitHub en fin de journée afin d’avoir une trace avec le dossier correspondant.

---

<a name="exo02">

### Exo 2

Réaliser un fichier HTML qui aura cette apparence :

Bonjour, bonne année **2017**, bonne santé et surtout : _Meilleurs vœux !_

---
<a name="exo03">

### Exo 3

Réaliser un fichier HTML qui aura l’apparence suivante :

# Mon repas de Noël

J’ai eu la chance d’avoir un repas de Noël _excellent_, puisqu’il était composé des plats
suivants :

- Du foie gras sur des toasts grillés _(ça j’adore)_
- Du saumon rose
- De la pintade avec une purée
- Une bûche glacée

Et le tout arrosé de **Champagne !**

Après, j'ai pu déballer tous mes cadeaux :

1. Mamie Lulu : des **DVD**

2. Mamie Elisabeth : des _CD_

3. Tonton Hugues : des **_livres_**

---
<a name="exo04">

### Exo 4

Réaliser un fichier HTML nommé "exo_04.html" dans lequel il faudra obtenir l'affichage suivant avec le navigateur :

N’oubliez pas de lire aussi le contenu, il fait partie des informations de base que tout développeur intégrateur web maîtrise. Les liens sont accessibles dans Le repo GitHub de Ma6Tvacoder.

# HTML - Exo 4

1. HTML: HyperText Markup Language
  - c'est la structure de la page html où on organise les titres, paragraphes, listes, tableaux...

2. CSS: Cascading Style Sheet
  - C'est la mise en forme, le design, l'apparence (les couleurs, les tailles, les positionnements sur la page)
  
3. Terminologie
  - Eléments : ils définissent la structure et le contenu des objets au sein d'une page. Les plus couramment utilisés sont les niveaux de titre (h1 à h6) et les paragraphes (avec la balise p)
  - Balises : elles sont reconnaissables car elles sont encadrées d'un chevron ouvrant et d'un chevron fermant. L'ouverture d'une balise détermine le début d'un élément. Sa fermeture détermine sa fin. Le contenu qui est inséré entre une balise ouvrante et fermante représente le contenu de cet élément. Par exemple, un lien html sera encadré d'une balise A ouvrante et fermante. Il existe aussi des balises auto-fermantes (aussi dites orphelines).
  - Attributs : ce sont des propriétés utilisées pour fournir des informations complémentaires sur un élément. Les attributs les plus communs incluent l'attribut ID (qui identifie un élément), l'attribut CLASS (qui classifie un élément), l'attribut SRC (qui spécifie la source d'un contenu qui peut être imbriqué) et l'attribut HREF (qui contient un lien hypertexte vers une ressource liée). Les attributs sont définis au sein de la balise ouvrant après le nom de l'élément :
  
  ```
  <a href="https://github.com/Ma6Tvacoder-Docs/partages">Lien</a>
  ```

4. Structure
  - un fichier HTML est un fichier de texte brut (non mis en forme) enregistré avec l'extension _.html_.
  - tous les fichiers html ont une structure de base qui implique de déclarer les éléments suivants :
  
    ```
     <!DOCTYPE html>
      <html>
        <head></head>
        <body>

        </body>
      </html>
    ```
    
  - **!DOCTYPE html** informe le navigateur web que le document est de type html et qu'il s'agit (ici) de la dernière version du langage
  - à l'intérieur de l'élément _html_ la balise **head** identifie le début du document et inclut les métadonnées (informations sur la page). Le contenu à l'intérieur de la balise head n'est pas affiché par le navigateur puisqu'il donne des informations sur la page (- liens vers des fichiers externes, utilisation du langage html, titre de la page).
  - tout ce qui s'affichera dans le navigateur est inclus à l'intérieur de la balise **body**.
  - quand un élément est placé au sein d'un autre (ou imbriqué) il est important d'**indenter** cet élément en le décalant vers la droite à l'aide de la tabulation pour conserver une structure bien organisée et lisible pour tout le monde.
  - les balises en paires comportent une balise ouvrante et une balise fermante indiquant pour chacune le début et la fin de l'élément correspondant.
  - les balises auto-fermantes correspondent à des éléments ponctuels dans une page html, pas besoin de fournir une information de fin (insérer une image ou un lien par exemple). Les plus courantes :
  
    ```
    <br />
    <img />
    <meta />
    <input />
    <hr />
    <link />
    ```
    
5. Le W3C - La validation du code

Le **World Wide Web Consortium**, abrégé par le sigle **W3C**, est un organisme de standardisation à but non lucratif, fondé en octobre 1994 chargé de promouvoir la compatibilité des technologies du [World Wide Web](https://fr.wikipedia.org/wiki/World_Wide_Web) telles que [HTML5](https://fr.wikipedia.org/wiki/HTML5), [HTML](https://fr.wikipedia.org/wiki/Hypertext_Markup_Language), [CSS](https://fr.wikipedia.org/wiki/Feuilles_de_style_en_cascade), [PNG](https://fr.wikipedia.org/wiki/Portable_Network_Graphics), [SVG](https://fr.wikipedia.org/wiki/Portable_Network_Graphics)…
 
Le [W3C ou World Wide Web Consortium](http://www.w3.org), est un organisme international qui développe des [standards](http://www.w3.org/standards/) pour le Web afin que les gens puissent communiquer efficacement à travers Internet, autour de formats ouverts garantissant une meilleure interopérabilité (c'est-à-dire une meilleure compréhension des systèmes hétérogènes à travers des données et langages standardisés).

Le consortium existe depuis 1994 et est dirigé par l'inventeur du Web, Tim Berners-Lee.
   
Il est composé d'une équipe fixe et des membres (dont plusieurs centaines d'entreprises partenaires). Les membres délèguent des ingénieurs au sein du W3C et participent ainsi à l'élaboration des spécifications techniques pour les technologies du Web. De nombreux membres actifs font partie des équipes de développement des navigateurs (Microsoft, Mozilla, Apple, Opera, Google, etc).
