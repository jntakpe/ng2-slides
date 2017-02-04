Marche aussi avec les attributs des composants

    <my-component name="{{user.name}}"></my-component>
    <my-component [name]="user.name"></my-component>


Si la valeur est statique
    
    <my-component name="John Doe"></my-component>

Il est aussi possible d'utiliser des fonctions

    <my-component [name]="findUsername()"></my-component>

`` Plus besoin de retenir les directives spécifiques de ng1``
