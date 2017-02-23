# Les Langages de Programmation

[Ajax JS](#AjaxJs)


![alt text](http://tutos-django.com/uploads/ajax.png "Logo AjaxJs")



## AJAX JS
<a name="AjaxJs"/>

Asynchronous Javascript And XML ou plus simplement AJAX, n'est pas à proprement parler un langage de programmation mais plutôt 
un moyen d'en utiliser plusieurs conjointement.

Il fonctionne en utilisant JavaScript en arrière plan pour communiquer avec le serveur et permettre la mise à jour de la page 
(envoi/réception d'information) en temps réel sans actualisation de la page.

On retrouve notamment ce langage dans 
* l'interface de Gmail 
* Google Talk 
* ou sur Facebook pour gérer les photos et le chat.


### Exemple de script:

```javascript
<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="UTF-8">
    <title></title>
    <link rel="stylesheet" media="screen" href="style.css">
    <script src="http://code.jquery.com/jquery-1.6.2.min.js"></script> <!-- Les sources de la bibliothèque JQuery -->
    <script src="script.js"></script> <!-- La source qui contient le code d'envoi en Ajax -->
  </head>
  <body>
    <form method="post" action="add.php"> <!-- Formulaire envoyé par la méthode POST -->
      <fieldset>
	<legend>Choisissez deux nombres entiers</legend>
	<p><label>a = <input name="a" type="number" required></label></p> <!-- Premier nombre -->
	<p><label>b = <input name="b" type="number" required></label></p> <!-- Deuxième nombre -->
      </fieldset>
      <fieldset>
	<legend>R&eacute;sultat</legend>
	<p id="result"></p> <!-- Le résultat sera placé ici -->
      </fieldset>
      <p><button>Soumettre</button></p> <!-- Bouton de soumission -->
    </form>
  </body>
</html>
```
