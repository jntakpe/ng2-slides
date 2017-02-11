## Formulaire

Un formulaire est représenté par un *FormGroup*

* *valid* : si le formulaire est valide
* *errors* : objet contenant les erreurs du formulaire
* *dirty* : false jusqu'à ce que l'utilisateur modifie un des champs du formulaire
* *pristine* : opposé de dirty
* *touched* : false jusqu'à ce que l'utilisateur soit entré et sorti d'un des champs du formulaire
* *untouched* : opposé de touched
* *value* : la valeur du formulaire sous forme de clé/valeur avec le nom du champ en clé
* *valueChanges* : un observable emettant la valeur du formulaire à chaque changement sur un des champs
