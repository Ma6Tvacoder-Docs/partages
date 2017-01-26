<a name="html">
##HTML

**_Definition: Language structurel_**

L’HyperText Markup Language, généralement abrégé HTML, est le format de données conçu pour représenter les pages web. C’est un langage de balisage permettant d’écrire de l’hypertexte.
Un document HTML contient des balises qui permettent d'être utilisées d'une certaine façon pour décrire correctement la structure d'un document.
Les balises indiquent au navigateur comment afficher le document, certaines balises permettent d'intégrer différents médias comme des images, des vidéos ou des musiques parmi le texte de la page.

**_Fonction_**

L’HyperText Markup Language permet de structurer sémantiquement et de mettre en forme le contenu des pages, d’inclure des ressources multimédias dont des images, des formulaires de saisie, et des programmes informatiques. Il permet de créer des documents interopérables avec des équipements très variés de manière conforme aux exigences de l’accessibilité du web. Il est souvent utilisé conjointement avec des langages de programmation (JavaScript) et des formats de présentation (feuilles de style en cascade)


###fichier d'exemple

    <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
    <html>
      <head>
        <title>HTML</title>
      </head>

      <body bgcolor="#FFFFE8" topmargin="5">

     <!-- Début Top Menu -->
             <a name="top"></a>
             <table border="0" cellpadding="0" cellspacing="0" width="771" align="center">
                 <tr>
                   <td width="200" align="left">
                       <a href="http://www.softastuces.com" title="Accueil de SoftAstuces"><img src="/images/tuto/base_site/logo.gif" width="200" height="60" border="0" alt="SoftAstuces.com"></a>
                   </td>
                   <td width=571 valign="middle">
                       <a href="/astu/index.php"><font color="#400040" size="+1">Les Astuces</font></a> | 
                       <a href="/tuto/index.php"><font color="#860411" size="+1">Les Tutoriaux</font></a> | 
                       <a href="javascript:;"><font color="#0000A0" size="+1">Le Forum</font></a> | 
                       <a href="/download/index.php"><font color="#808080" size="+1">Zone Download</font></a>
                   </td>
                 </tr>
             </table>
         <!-- Fin Top Menu -->
         </body> 
     </html>
     
# QU'EST CE QUE LE CSS ?

### 1. CSS ( Cascadings Style Sheet)  est un langage 
qui décrit le style d'un document HTML, il va 
informé au navigateur comment les éléments HTML doivent etres afficher et va permettre a la mise en forme & la présentation des documents HTML et XML.
Un site web peut être constitué par une simple page statique au format HTML 
éventuellement mise en forme ou enrichie de CSS incluant des images et des liens vers d'autres contenus.

### 2. UTILISATION
CSS ? C'est lui qui vous permet de choisir la couleur de votre texte.
Lui qui vous permer de sélectionner la police utilisée sur votre site.
Lui encore qui permet de définir la taille du texte, les bordures, le fond...
Et aussi, c'est lui qui permet de faire la mise en page de votre site. Vous pourrez dire : je veux que mon menu
soit à gauche et occupe telle largeur, que l'en-tête de mon site soit calé en haut et qu'il soit toujours visible, etc.

   ![image](https://user.oc-static.com/files/339001_340000/339428.png)

<a name="framwork">
# *FRAMEWORK*

## Définition

Un framework est un ensemble d'outils et de composants logiciels organisés conformément à un plan d'architecture et des **patterns**, l'ensemble formant ou promouvant un « squelette » de programme. Il est souvent fourni sous la forme d'une bibliothèque logicielle, et accompagné du plan de l'architecture cible du framework.

Un framework est conçu en vue d'aider les programmeurs dans leur travail. L'organisation du framework vise la productivité maximale du programmeur qui va l'utiliser — gage de baisse des coûts de construction et maintenance du programme. Le contenu exact du framework est dicté par le type de programme et l'architecture cible pour lequel il est conçu.

On trouve différents types de frameworks :

+ framework d'infrastructure système : pour développer des systèmes d'exploitation, des interfaces graphiques, des outils de communication (exemple : Framework .Net, Struts) ;
+ framework d'intégration intergicielle (middleware) : pour fédérer des applications hétérogènes. Pour mettre à disposition différentes technologies sous la forme d'une interface unique ;
+ frameworks d'entreprise : pour développer des applications spécifiques au secteur d'activité de l'entreprise ;
+ frameworks de gestion de contenu : sont les fondations d'un système de gestion de contenu — pour la création, la collecte, le classement, le stockage et la publication de « biens numérisés ».

Les principaux avantages de ces frameworks sont la réutilisation de leur code, la standardisation du cycle de vie du logiciel (spécification, développement, maintenance, évolution), ils permettent de formaliser une architecture adaptée au besoin de l'entreprise. Ils tirent parti de l'expérience des développements antérieurs.

**Patterns** : Le mot anglais « pattern » est souvent utilisé pour désigner un modèle, une structure, un motif, un type, etc. Il s'agit souvent d'un phénomène ou d'une organisation que l'on peut observer de façon répétée lors de l'étude de certains sujets, auquel il peut conférer des propriétés caractéristiques.

<a name="Bootstrap">
# Bootstrap

## Définition 

Bootstrap est un outil développé par Mark Otto et Jacob Thorton, alors ingénieurs chez Twitter, pour encourager leur équipe d’ingénieurs à utiliser le même framework et donc minimiser ces incohérences.
Pour faire simple, Bootstrap est une compilation de plusieurs éléments et fonctions web-design personnalisables, le tout emballé dans un seul et même outil. 

## Utilisation

Les développeurs qui utilisent Bootstrap pour la création de leur site web choisissent les éléments qu’ils veulent utiliser avec la certitude qu’ils ne seront pas incompatibles entre eux. Bootstrap est connu et le plus populaire des frameworks front-office pour développer des projets responsive et mobile-first sur le web. 

## Utilisation du code


| *Exemple de code bootstrap* |
|---|

```
<!-- Bootstrap core CSS -->
   <link href="../../dist/css/bootstrap.min.css" rel="stylesheet">  
   <nav class="navbar navbar-inverse navbar-fixed-top">
     <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">Project name</a>
        </div>
        <div id="navbar" class="collapse navbar-collapse">
          <ul class="nav navbar-nav">
            <li class="active"><a href="#">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div><!--/.nav-collapse -->
      </div>
    </nav>
    
  ```
  

    
Tout cela laisse présager de bonnes nouvelles pour les développeurs et les webmasters. Restez connectés pour la 2ème partie dans laquelle j’aborderai les raisons pour lesquelles intégrer Bootstrap à votre site web est la meilleure chose que vous pourriez faire. Merci de nous lire, n’hésitez pas à laisser vos commentaires sur Prestashop et Bootstrap ci-dessous !

