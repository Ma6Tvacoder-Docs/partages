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
code JavaScript depuis votre document HTML, vous aurez besoin de l'élément <script>.

Il y a deux méthodes pour utiliser script : 
une qui sert lorsqu'on souhaite utiliser un script contenu dans un fichier tiers et une qui sert lorsqu'on intègre directement le 
code du script dans la page web.
Généralement, un script est écrit dans un fichier .js à part. Pour exécuter un script depuis un fichier dans la page web, il suffira 
d'utiliser <script> avec un attribut src pointant vers le fichier du script en utilisant l'URL du fichier :

    <script src="chemin/vers/le/script.js"></script>
