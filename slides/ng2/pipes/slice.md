## Slice

Renvoi un sous-ensemble d'un tableau ou chaine de caractères

        <p>{{users | slice:0:2 | json}}</p>
Affichera les 2 premiers éléments du tableau

        <p>{{ 'Formation Angular' | slice:0:9}}</p> <!-- Formation -->

Affichera 'Formation'

        <p>{{ 'Formation Angular' | slice:-7}}</p> <!-- Angular -->

Affichera 'Angular'
