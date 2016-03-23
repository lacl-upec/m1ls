TP de langage de spécification
==============================

Partie 2
--------

Déclarer une machine B pour représenter l'affectation des cours aux salles disponibles pour chaque créneau de la semaine. On utilisera un ensemble abstrait pour les cours et les salles.

- Les créneaux durent 1h30, commencent à 8h avec 15mn de battement entre chaque créneau et seront représentés par un couple *(jour,heure de début)*
- Une variable fera correspondre à chaque cours le nombre de créneaux hebdomadaires nécessaire pour le cours.
- Il ne peut pas y avoir deux cours dans la même salle

On indiquera dans l'invariant le respect des deux dernières consignes.

Écrire les opérations suivantes. Chacune retournera un booléen égal à TRUE si l'opération à été possible et FALSE sinon

- `placeCours` qui choisi des créneaux pour le cours passé en paramètre
- `placeCoursMatin` qui choisi des créneaux le matin pour le cours passé en paramètre
