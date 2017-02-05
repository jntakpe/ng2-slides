## Currency

Permet d'afficher des monnaies avec les paramètres suivants :

- le code ISO de la devise ('EUR', 'USD')
- un booléen indiquant si on souhaite utiliser le symbole ('€', '$')
- la chaîne de formatage du montant dans le même format que *number*

        <p>{{ 20.8 | currency:'EUR' }}</p> <!-- EUR20.80 -->
        <p>{{ 20.8 | currency:'USD':true }}</p> <!-- $20.80 -->
        <p>{{ 20.8 | currency:'USD':true:'.3' }}</p> <!-- $20.800 -->
