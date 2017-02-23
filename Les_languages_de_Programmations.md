#L'Assembleur(ASM):

inventé en 1945 par John von Neumann, l'assembleur fut le premier vrai langage de programmation mais aussi le plus proche
de langage machin.

![image](http://www.lopr.net/Images/ASM.gif)

#Le COBOL:

common Organization Business Oriented Language. Datant de 1959, ce langage de programmation
contrairement au C++ ou au Java, il n'est pas orienté objet.


exemple

         01 NomPrenom.

         05 Prenom PIC X(20).

         05 Nom    PIC X(20).



#Le BASIC:

Beginners All purpose Simple Intructions Code (1964) le langage de programmation le plus simple
il permet de créer des programmes basiques .
exepemple:

           0 INPUT "Quel est votre nom ? "; NOM$ 

           20 PRINT "Bonjour "; NOM$

           30 INPUT "Combien d'étoiles voulez-vous ? "; NOMBR



#Le Pascal:
est né dans les années 70connu son essor à partir de 1983 avec le compilateur turbo Pascal (de la société Borland)
il évolua pour incorporer des objets puis pour être capable d'affficher des fenêtres.


exemple:
             PROGRAM var_entiere;

             VAR

             a : integer; { D´eclaration }

            BEGIN

             a := 5; { Affectation }

            writeln (’valeur de a = ’, a); { Affichage : a = 5 }


           end

#la programmation orientée objet (POO):

La programmation orientée objet consiste à représenter son programme sous la forme 
d'objets (ce peut être n'importe quoi) ayant leurs propres attributs et communiquant entre eux à l'aide de méthodes.

La programmation orientée objet devient de plus en plus indispensable de nos jours pour faire des programmes souples
bien conçus et maintenables. Elle est accompagnée de diverses notions: héritage, polymorphisme, upcast, classe/méthode abstrait
design patterns, etc.
