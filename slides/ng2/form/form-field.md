## Champ de formulaire

Un champ de formulaire est un *FormControl* :

* *valid* : si le champ est valide avec les validations et contraintes qui lui sont appliquées
* *errors* : objet contenant les erreurs du champ
* *dirty* : false jusqu'à ce que l'utilisateur modifie le champ
* *pristine* : opposé de dirty
* *touched* : false jusqu'à ce que l'utilisateur soit entré et sorti du champ
* *untouched* : opposé de touched
* *value* : la valeur du champ
* *valueChanges* : un observable emettant la valeur du champ à chaque changement
