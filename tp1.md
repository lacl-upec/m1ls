TP de langage de spécification
==============================

Opérations
----------

Déclarer une machine B sans variables avec les opérations suivantes :

- `somme` qui prend deux entiers et retourne leur somme
- `max` qui prend deux entiers et retourner leur maximum
- `nieme` qui prend une liste d'entiers et un indice `n` et retourne le `n`ième élément de la liste
- `elem` qui prend une liste d'entiers et retourne l'ensemble des éléments de la liste
- `elemPair` qui prend une liste d'entiers et retourne l'ensemble des éléments pairs de la liste
- `multiSet` qui prend une liste d'entiers et retourne le multi-ensemble des éléments sous la forme d'une fonction partielle qui à un élément associe le nombre d'occurrence de cet élément dans le multi-ensemble
- `tri` qui prend une liste et la retourne triée
- `decomp` qui prend un entier et retourne un objet mathématique représentant la décomposition en facteurs premiers cet ensemble


Machine
-------

Déclarer une machine B pour représenter l'affectation des cours aux salles disponibles pour chaque créneau de la semaine. On utilisera un ensemble abstrait pour les cours et les salles.

- Les créneaux durent 1h30, commencent à 8h avec 15mn de battement entre chaque créneau et seront représentés par un couple *(jour,heure de début)*
- Une variable fera correspondre à chaque cours un nombre de créneaux hebdomadaires
- Il ne peut pas y avoir deux cours dans la même salle

On indiquera dans l'invariant le respect des deux dernières consignes.

Écrire des opérations suivantes. Chacune retournera un booléen qui renvoi TRUE si l'opération à été possible et FALSE sinon

- `placeCours` qui choisi des créneaux pour le cours passé en paramètre
- `placeCoursMatin` qui choisi des créneaux le matin pour le cours passé en paramètre
- `placeCoursApres` qui choisi des créneaux pour un cours placé à un créneau suite après un autre
- `forceCoursApres` qui choisi des créneaux pour un cours placé à un créneau suite après un autre quitte à déplacer le premier