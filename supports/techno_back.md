[SQL](#sql)

<a name="sql">                                                                                                   
# SQL

##### **SQL** qui signifie ,langage de requête structurée, est un langage informatique normalisé servant à exploiter des bases de données relationnelles. La partie langage de manipulation des données de **SQL** permet de rechercher, d'ajouter, de modifier ou de supprimer des données dans les bases de données relationnelles.

__________




Le langage **SQL** s'utilise principalement de trois manières :

un programme écrit dans un langage de programmation donné utilise l'interface de programmation du SGBD pour lui transmettre des instructions en langage SQL. Ces programmes utilisent des composants logiciels tels que ODBC ou JDBC. Cette technique est utilisée par l'invite de commande qui permet à un administrateur d'effectuer des opérations sur les bases de données, opérations qu'il décrit en **SQL** ;
technique dite embedded **SQL** :

des instructions en langage **SQL** sont incorporées dans le code source d'un programme écrit dans un autre langage ;
technique des procédures stockées : des fonctions écrites en langage **SQL** sont enregistrées dans la base de données en vue d'être exécutées par le SGBD. Cette technique est utilisée pour les trigger - procédures déclenchées automatiquement sur modification du contenu de la base de données.




__________


###### * ODBC (sigle de Open Database Connectivity) est un intergiciel qui permet à une application informatique, par un procédé unique, de manipuler plusieurs bases de données qui sont mises à disposition par des systèmes de gestion de bases de données (SGBD) ayant chacun un procédé propre.

###### * Une base de données est un outil permettant de stocker et de retrouver l'intégralité de données brutes ou d'informations en rapport avec un thème ou une activité ; celles-ci peuvent être de natures différentes et plus ou moins reliées entre elles 

###### *JDBC (Java DataBase Connectivity) est une interface de programmation créée par Sun Microsystems — depuis racheté par Oracle Corporation — pour les programmes utilisant la plateforme Java.

---------

<a name="ajax">
##AJAX JS

##### AJAX est l'acronyme d'Asynchronous JavaScript and XML, ce qui, transcrit en français, signifie « JavaScript et XML asynchrones ».
![alt text](http://javascriptsolution.com/wp-content/uploads/2016/05/AJAX_logo_by_gengns.svg_.png)

Derrière ce nom se cache un ensemble de technologies destinées à réaliser de rapides mises à jour du contenu d'une page Web, sans qu'elles nécessitent le moindre rechargement visible par l'utilisateur de la page Web. Les technologies employées sont diverses et dépendent du type de requêtes que l'on souhaite utiliser, mais d'une manière générale le JavaScript est constamment présent.
D'autres langages sont bien entendu pris en compte comme le HTML et le CSS, qui servent à l'affichage, mais ceux-ci ne sonts pas inclus dans le processus de communication. Le transfert de données est géré exclusivement par le JavaScript, et utilise certaines technologies de formatage de données, comme le XML ou le JSON.

* XML

Le XML, acronyme de eXtensible Markup Language (qui signifie: langage de balisage extensible), est un langage informatique qui sert à enregistrer des JSON (prononciation : /ʒi.sɔn/ (fr) ou /dʒej.sɔn/ (fr)1, ou /ˈdʒeɪˌsən/ (en)2), ou JavaScript Object Notation, est un format de données textuellesdonnées textuelles. Ce langage a été standardisé par le W3C en février 1998 et est maintenant très populaire. Ce langage , grosso-modo similaire à l'HTML de par son système de balisage, permet de faciliter l'échange d'information sur l'internet. 
Contrairement à l'HTML qui présente un nombre finit de balises, le XML donne la possibilité de créer de nouvelles balises à volonté.

* JSON

JSON ou JavaScript Object Notation, est un format de données textuelles dérivé de la notation des objets du langage JavaScript. Il permet de représenter de l’information structurée comme le permet XML par exemple.
Un document JSON a pour fonction de représenter de l'information accompagnée d'étiquettes permettant d'en interpréter les divers éléments, sans aucune restriction sur le nombre de celles-ci.

* Asyncrone 

Le terme "Asynchronous", asynchrone en français, signifie que l'exécution de JavaScript continue sans attendre la réponse du serveur qui sera traitée quand elle arrivera. Tandis qu'en mode synchrone, le navigateur serait gelé en attendant la réponse du serveur.

##**Pourquoi utiliser Ajax**


Ajax devient nécessaire dès lors que vous voulez réaliser un site ou des pages dynamiques et que celles-ci doivent charger de nouvelles données sur le serveur, après leur affichage, à la demande de l'utilisateur ou pour renouveller leur contenu.
Ajax permet de modifier partiellement la page affichée par le navigateur pour la mettre à jour sans avoir à recharger la page entière.
Par exemple le contenu d'un champ de formulaire peut être changé, sans avoir à recharger la page avec le titre, les images, le menu, etc. 
Ajax permet ainsi d'effectuer des traitements sur le poste client (avec JavaScript) à partir d'informations prises sur le serveur. Cela répartit la charge de traitement.
Auparavant, toutes les modifications de pages étaient faites sur le serveur ce qui nécessitait des échanges maintenant inutiles. 


<a name="CakePHP">

##CakePHP

![alt text](https://upload.wikimedia.org/wikipedia/fr/9/9a/Cake-logo.png)

----

####Definition:
====

CakePHP est un framework  il propose une structure au programmeur qui lui permet de développer plus vite et plus intuitivement.

####Utilisation:
====

- Cake facilite l'utilisation de Bases de données

- Dispatcheur d'URL permettant d'obtenir des adresses aisément lisibles

- Composants de sécurité, de gestion des droits et de gestion des sessions

####Exemple de codage CakePHP:
====

    $booleanVariable = true;
    $stringVariable = "moose";
    if ($booleanVariable) {
        echo "Valeur boléenne si true";
        if ($stringVariable === "moose") {
            echo "Nous avons rencontré un moose";
        }
    }
    
####Lien vers le site web du framework: 
====

[cakePHP](https://cakephp.org/)


<a name="Symphony 3">

##Symfony

![alt text] (https://symfony.com/images/v5/logos/header-logo.svg)

---

Symfony est un web framework php, c'est a dire un ensemble d'outils facilitant la conception d'un site web en language PHP. 
C'est l'un des framework les plus utilisés au monde, produit par une société francaise.
L'utilité étant, pour les dévellopeurs, d'écourter les taches usuelles tout en respectant les conventions de codage. 
L'experience utilisateur et le travail des autres acteurs (admin système, etc) ne devrait en aucun cas etre affecté.

---

Le framework Symfony est utilisé pour le développement web, étant un framework du langage PHP utilisé très majoritairement pour la 
conception de pages web dynamiques, en tant que langage script coté serveur (back-end).

Le PHP, qui était a la base une bibliothèque logicielle du langage C, est désormais le langage de programmation web back-end 
le plus utilisé au monde. Le PHP sert a traiter et générer le code final de la page qui sera affichée a l'utilisateur web.

Un petit exemple de code en PHP:

    <?php

    // la fonction strtolower renvoie en minuscules la chaîne de caractères passée en paramètre
    $lang = strtolower($_POST['lang']);

    if ($lang === 'fr')
    echo 'Vous parlez français !';
    elseif ($lang === 'en')
    echo 'You speak English!';
    else
    echo 'Je ne vois pas quelle est votre langue !';

---

[Lien vers le site de Symfony](https://symfony.com/what-is-symfony)

<a name="Node.js">

##Node.js
![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/langfr-170px-Node.js_logo.svg.png)
---

Node.js est une plateforme logicielle libre et événementielle en JavaScript orientée vers les applications réseau qui doivent pouvoir monter en charge. ... Concrètement, node.js est un environnement d'assez bas niveau permettant d'exécuter du javascript non plus dans le navigateur web mais sur le serveur.

---

####Assez bas niveau
Un langage de programmation est dit de bas niveau lorsque le codage de celui-ci se rapproche du langage machine (dit « binaire »), et donc permet de programmer à un degré très avancé. Les langages de bas niveau sont à opposer aux langages de haut niveau, qui permettent de créer un programme sans tenir compte de la façon dont fonctionne le matériel de l'ordinateur censé exécuter le programme.
   
    
---
    

####exemple de code en Node.js

    var http = require('http');
    var server = http.createServer(function(request, response){
        response.writeHead(200, {'Content-Type': 'text/plain'});
        response.end('Hello World\n');
    });

    server.listen(3000);

    console.log('Adresse du serveur: http://localhost:3000');


---

####Lien du site web du framework

[Node.js](https://nodejs.org/)

