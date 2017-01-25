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
