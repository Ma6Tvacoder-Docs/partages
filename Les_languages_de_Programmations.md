
# [Jquery](#jLink)








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
