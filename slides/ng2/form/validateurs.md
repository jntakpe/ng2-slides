## Validateurs

Un validateur retourne une map d'erreurs ou *null* si aucune erreur est détectée.

Quelques validateurs : 

* *required* qui permet de vérifier que le champ n'est pas vide
* *minLength(n)* qui permet de vérifier la longueur minimum
* *maxLength(n)* qui permet de vérifier la longueur maximum
* *pattern(p)* qui permet de vérifier le respect d'une regex
