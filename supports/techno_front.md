##Menu
[Bootstrap](bootstrap)

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

<a name=JavaScript>
#**Javascript** 

##*Définition*
Le JavaScript est un langage informatique utilisé sur les pages web. Ce langage à la particularité de s'activer sur le poste client, 
en d'autres mots c'est votre ordinateur qui va recevoir le code et qui devra l'exécuter. C'est en opposition à d'autres langages qui 
sont activé côté serveur. L'exécution du code est effectué par votre navigateur internet tel que Firefox ou Internet Explorer.

##*Ce que cest*
Javascript est un langage de programmation, c’est une forme de code qui permet, quand on sait l’écrire, de dicter à l’ordinateur quoi 
faire. C’est du texte. Juste du texte. Comme une autre langue. On trouve la majorité du code Javascript dans des pages Web, même si 
vous ne le voyez pas s’afficher. En effet, c’est le seul langage qui permette de dicter à un navigateur Web (Internet Explorer, Firefox,
Chrome…) ce qu’il doit faire sans rien installer. La grande majorité des navigateurs Web “parlent” le Javascript.

Le code Javascript ressemble à ça :

    setTimeout(function(){

        if (truc == machin) {
     
         alert('Bidule !')
     
        }
   
    }, 100)

##*Ce qu'on peut faire avec*
La plupart du code Javascript se trouve dans des pages Web, et sert donc à dire comme la page Web doit réagir. Cela marche ainsi :

L’utilisateur clique sur un lien ou entre une adresse.
Son navigateur charge la page Web. Il voit le texte, les couleurs, les images.
Si la page Web contient du code Javascript, le navigateur lit le code Javascript et suit les instructions du code.
Généralement le code Javascript dans une page Web sert à :

Faire bouger, apparaitre ou disparaitre des éléments de la page (un titre, un menu, un paragraphe, une image…).
Mettre à jour des éléments de la page sans recharger la page (changer le texte, recalculer un nombre, etc).
Demander au serveur un nouveau bout de page et l’insérer dans la page en cours, sans la recharger.
Attendre que l’utilisateur face quelque chose (cliquer, taper au clavier, bouger la souris…) et réagir (faire une des opérations 
ci-dessus suite à cette action).
Le code Javascript sert donc à donner du dynamisme à la page. Sans lui, la page ressemble à une page de livre, un peu animée 
(grâce à un autre langage appelé le CSS), mais qui ne change pas beaucoup.
Par exemple, voici quelques fonctionnalités que l’on peut voir dans une page Web qui impliquent Javascript :

Un menu accordéon.
Un sélecteur de date.
Une barre de progression.
Cela ne veut pas dire qu’on ne pourrait pas avoir ces fonctionnalités avec autre chose que Javascript, mais dans notre cas, 
elles ont été produites avec Javascript.

Certains sites Web ne pourrait tout simplement pas fonctionner sans Javascript. C’est le cas de Facebook, Youtube ou Twitter qui 
utilisent le langage pour presque tout leur affichage. La page de recherche de Google, en revanche, peut fonctionner sans Javascript.

##*Javascript, en dehors d’un navigateur Web*
Avec l’amélioration des performances de Javascript, le langage a été de plus en plus utilisé en dehors du navigateur Web. 
On le retrouve aujourd’hui un peu partout :

Sur les serveurs, l’exemple le plus célèbre étant NodeJS, un outil qui permet de générer les pages Web avant de les envoyer au 
navigateur.Sur les interfaces des ordinateurs, il permet d’afficher des fenêtres et des boutons (Scripting QT, Gnome Shell).
Sur les téléphones, pour le moment sur FirefoxOS et PhoneGap, il permet d’écrire des applications.

##*Comment déclencher le code JavaScript depuis le document HTML*
Dans un navigateur, JavaScript ne fait rien « tout seul ». Il a besoin d'être lancé depuis les pages web HTML. Pour appeler du 
code JavaScript depuis votre document HTML, vous aurez besoin de l'élément `<script>`.

Il y a deux méthodes pour utiliser script : 
une qui sert lorsqu'on souhaite utiliser un script contenu dans un fichier tiers et une qui sert lorsqu'on intègre directement le 
code du script dans la page web.
Généralement, un script est écrit dans un fichier .js à part. Pour exécuter un script depuis un fichier dans la page web, il suffira 
d'utiliser `<script>` avec un attribut src pointant vers le fichier du script en utilisant l'URL du fichier :

    <script src="chemin/vers/le/script.js"></script>
    
<a name="jquery" >
# Jquery
## Définition

jQuery est une bibliothèque ou framework Javascript sous licence libre et multiplateforme qui permet de faciliter des fonctionnalités communes de Javascript.Jquery est utilisable sur plusieurs navigateurs web.

##Utilisation

Jquery propose comme prinpale fonctionnalités de développer des plug ins,la manipulation du Document Object Model, la gestion des évènements ( mouvements de souris,clics,etc),de l'AJAX,la création d'effets d'animation,la manipulation des feuilles de style en cascade.La bibliothèque Jquery permet aussi de gagner en rapidité dans l'interaction avec le code HTML d'une page Web.Ce framework ne nécéssite aucun installation particulière et peut être téléchargé depuis le site officiel https://jquery.com/ .

## Exemple de code Jquery

```

$( function() {
    var state = true;
    $( "#button" ).on( "click", function() {
      if ( state ) {
        $( "#effect" ).animate({
          backgroundColor: "#aa0000",
          color: "#fff",
          width: 500
        }, 1000 );
      } else {
        $( "#effect" ).animate({
          backgroundColor: "#fff",
          color: "#000",
          width: 240
        }, 1000 );
      }
      state = !state;
    });
  } );

<a name="bootstrap">
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

