# MCD
Dans la méthode Merise destinée à créer des bases de données, il ya des outils dédiés aux traitements et aux données.
Le MCD (modèle conceptuel des données) est un des outils majeurs concernant les donnnées.

Le MCD est une représentation graphique de haut niveau qui permet facilement et simplement de comprendre comment les différents éléments sont liés entre eux à l’aide de diagrammes codifiés dont les éléments suivants font partie :

Les entités (1 rectangle = 1 objet) ;
Les propriétés (la liste des données de l’entité) ;
Les relations qui expliquent et précisent comment les entités sont reliées entre elles (les ovales avec leurs « pattes » qui se rattachent aux entités) ;
Les cardinalités (les petits chiffres au dessus des « pattes ») :
Les cardinalités sont des couples de valeur que l'on trouve entre chaque entité et ses
associations liées. pour une association de 2 entités, il y a 4 cardinalités à indiquer (2 de chaque côté).
Il y a trois valeurs typiques : 0, 1 et N (plusieurs). Pour les associations à 2 entités, ce sont des valeurs qui permettent d’indiquer combien de fois
au minimum et au maximum une occurrence d'entité peut être liée à une autre occurrence
d'entité. 

Les assocoations :
[1,n] [n,n] [1,1]


Utilisé assez tôt en conception de base de données, le MCD évoluera ensuite vers les autres outils de Merise, à savoir le MPD et le MLD.

Cet outil permet d’échanger entre informaticiens et non-informaticiens sur l’outil à informatiser. On peut ainsi à partir d’un MCD valider et préciser des règles qui s’appliqueront à la future base de données :
