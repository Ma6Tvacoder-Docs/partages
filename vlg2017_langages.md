# Ajax (Asynchronous Javascript and Xml) :

L'architecture informatique Ajax permet de construire des applications Web et des sites web dynamiques interactifs (`*`) sur le poste client en se servant de différentes technologies ajoutées aux navigateurs web


Par exemple, sur une page web, il y a  deux champs à renseigner, chacun  à partir d'une liste déroulante prédéfinie par des données contenues en base de données. Le premier champs demande une région française. Le deuxième champs demande un département parmi ceux récupérés à partir du choix de la région choisie.

Ajax permet d'aller chercher les départements de la région choisie sans en restant sur la même page web.

Sans Ajax, on verra la page qui se recharge après avoir récupéré les départements.



## Exemple de code qui serait éxécuté à la suite du choix d'une région (code Javascript) :

**1** xhrj = new XMLHttpRequest();  
**2** xhrj.open('GET', 'modele/listededepartements.php?id_region=3';  
**3** xhrj.send(null);  
**4** pr = xhr.responseText;

https://openclassrooms.com/courses/ajax-et-l-echange-de-donnees-en-javascript/le-concept-d-ajax#/id/r-244366
