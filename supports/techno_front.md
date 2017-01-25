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


