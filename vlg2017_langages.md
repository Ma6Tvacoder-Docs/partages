# les langages de programmation #
* ## SQL   Sandra ##

 Le langage SQL (Structured Query Language) permet de dialoguer avec la base de données. il existe différentes versions du langage SQL en fonction de la base de données utilisée. Mais SQL dispose également d'une syntaxe élémentaire, normalisée et indépendante de toute base de données.


*  Grâce au langage SQL, on peut rechercher certains enregistrements afin de les extraire, dans l'ordre dans lequel vous  on souhaite les extraire. Par exemple, vous pouvez créer une instruction SQL qui extrait les informations de plusieurs tables simultanément, ou alors un enregistrement spécifique.

* Pour ce faire, nous allons utiliser l'instruction SELECT : cette instruction est utilisée pour renvoyer des champs spécifiques d'une ou de plusieurs tables de la base de données.  

* Par exemple, cette instruction

* | SELECTE Artiste, titre | FROM Musique |

*   … renverra la liste des Artistes et des Titres de tous les      enregistrements de la table Musiques.
Vous pouvez aussi utiliser le symbole « * » à la place de la liste des champs pour lesquels vous souhaitez la valeur :

* | SELECT * | FROM Musique |

*   Ainsi, cette requête vous renverra un tableau contenant toutes les informations sur toutes les musiques présentes dans la table.

* Nous pouvons aussi limiter le nombre d'enregistrements sélectionnés. Nous allons pour cela utiliser un ou plusieurs champs qui vont permettre de filtrer la recherche. Nous allons maintenant voir certaines clauses disponibles qui permettront ce filtrage.

  **La clause WHERE**

* La clause WHERE va permettre de spécifier les conditions : seule une partie des enregistrements seront concernés.
Prenons un exemple : nous voulons retrouver les informations concernant le titre Nothing Else Matters.

| SELECT * | FROM Musique | TITRE= 'Nothing else matters'|
| -------- | ------------ | ---------------------------- |

* Vous avez sûrement remarqué les guillemets : lorsque l'on     utilise la syntaxe de la clause WHERE, les guillemets servent de délimiteurs de chaînes de caractères.
* Vous avez sûrement remarqué les guillemets : lorsque l'on utilise la syntaxe de la **clause WHERE**, les guillemets servent de délimiteurs de chaînes de caractères.
On peut traduire la commande **WHERE** par **« où »** en français, donc l'instruction **WHERE Titre = 'Nothing Else Matters' peut se traduire par « où le champ Titre est égal à Nothing Else Matters ».**


* Il existe en **SQL** des conditions associées à la clause WHERE tout comme en VB .NET :

| condition | valeur |  
| --------- | ------ |  
| = | égal |
| != | différent |
| > | inférieur |
| < | superieur |
| >= | inferieur ou égal |
| AND ou && | et |
| OR  | ou |

* Par exemple :

| SELECT * | FROM Musique | WHERE Titre !='Nothing else matters' |
| -------- | ------------ | ------------------------------------ |

Ce code affichera toutes les informations dont le champ est différent de Nothing Else Matters. Nous allons maintenant découvrir d'autres conditions de la clause WHERE…

La clause **WHERE… IN**

Cette clause permet de renvoyer tous les enregistrements qui répondent à une liste de critères.
Par exemple, nous pouvons rechercher les artistes nés en France :

| SELECT * | FROM Artistes | WHERE Pays IN ('France') |
| -------- | ------------- | -------------------------|

**Clause WHERE… BETWEEN**

Nous pouvons sélectionner quelques enregistrements se trouvant entre deux critères de recherche spécifiés. La requête suivante permet de récupérer la liste des albums de l'année 2011 :


| SELECT *  FROM Albums | WHERE DateSortieAlbum BETWEEN |  '01/01/11' AND '31/01/11' |
| --------------------- | ----------------------------- |

ous remarquerez l'utilisation de AND pour dire « et » : « Entre… et… ».
**La clause WHERE… LIKE**

Cette clause permet de renvoyer tous les enregistrements pour lesquels il existe une condition particulière dans un champ donné. Ci-dessous la commande qui permet de rechercher tous les artistes dont le nom commence par un « s » :

| SELECT * | FROM Artistes | WHERE Nom LIKE 's%' |
| -------- | ------------- | ------------------- |

Le symbole % est utilisé pour remplacer une séquence de caractères quelconque.
Et enfin, une dernière clause un peu différente de celles vues jusqu'à maintenant…

**La clause ORDER BY**

**La clause ORDER** BY permet de renvoyer les enregistrements dans un ordre donné. Il en existe deux :

| obtion | tracduction |
| ------ | ----------- |
| ASC  | ordre croissant |
| DESC | ordre décroissant |

Il peut y avoir plusieurs champs spécifiés comme ordre de tri. Ils sont analysés de la gauche vers la droite.


* Ajouter des informations
Grâce au SQL, nous pouvons aussi ajouter des informations dans une table avec la commande INSERT INTO. Pour ce faire, il faut indiquer la table dans laquelle on souhaite intégrer une ligne ainsi que la liste des champs pour lesquels on spécifie une valeur, et enfin la liste des valeurs correspondantes. Voyons cela avec un petit exemple :

* on utilise INSERT INTO en spécifiant à côté dans quelle table nous allons ajouter des informations (ici la table Musiques) ; ensuite, entre parenthèses, on déclare la liste des champs dans lesquels nous allons entrer des valeurs. Le mot-clé VALUES va permettre d'entrer les données entre parenthèses, on entre les informations dans le même ordre que celles d'avant VALUES.

* Il y a un moyen de raccourcir le code précédent :

  En effet, lors du dernier code j'avais spécifié les champs dans lesquels je voulais entrer des valeurs, mais j'avais spécifié tous les champs de la table Musiques ! Donc au lieu de mettre tous les champs qui composent cette table, j'ai le droit de déclarer uniquement le nom de la table dans laquelle je souhaite ajouter des informations.

* Si vous n'indiquez pas de valeur pour un certain champ dans une table, celui-ci doit prendre la valeur **NULL** par défaut : l'instruction **INSERT** exige que tous les champs soient remplis. Donc vous devez mettre **NULL** si vous n'avez aucune information à placer dans un champ.

    La mise à jour d'informations
  On peut modifier certains champs d'enregistrements existants grâce au mot-clé **UPDATE** : cette instruction permet de mettre à jour plusieurs champs de plusieurs enregistrements d'une table, à partir des expressions qui lui sont fournies.

  Pour ce faire, vous devez indiquer le nom de la table à mettre à jour ainsi que les nouvelles valeurs à affecter aux champs.

  Le mot-clé SET va permettre cette affectation.

  Si l'on veut que les modifications ne se fassent que sur un ensemble limité d'enregistrements, on doit utiliser la clause WHERE. Si aucune clause n'est indiquée, la modification se fera sur tous les enregistrements de la table !

  Par exemple, pour modifier le titre d'une chanson , on utilise le code suivant :

  La modification du titre de la chanson ne portera ici que sur l'enregistrement qui porte le numéro 4 ! Tandis que si l'on souhaite que la mise à jour soit globale, inutile de mettre de clause.

* Supprimer des informations
  Il se peut que l'on soit amené à supprimer un ou plusieurs enregistrements d'une table, il existe pour cela l'instruction **DELETE FROM.** On doit alors fournir au minimum le nom de la table sur laquelle va s'effectuer la suppression.

  Si il y a uniquement le nom de la table de renseignée, alors tous les enregistrements de cette table seront supprimés.
Pour limiter la suppression, on réutilise la **clause WHERE.**
La commande suivante efface tous les enregistrements de la table Musiques :

  **SELECT** permet d'effectuer des recherches et de récupérer des données.

  **UPDATE** met à jour des données.

  **INSERT** ajoute des données.

  **DELETE** supprime des données.

  
