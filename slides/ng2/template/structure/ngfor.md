## NgFor

Permet d'afficher des listes d'éléments

    <ul>
      <template ngFor let-color [ngForOf]="colors">
        <li>{{color}}</li>
      </template>
    </ul>

Ou en syntaxe raccourcie
    
    <ul>
      <li *ngFor="let color of colors">{{color}}</li>
    </ul>

