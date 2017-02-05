## Async

Permet d'afficher des données obtenues de manière asynchrone
    
    @Component({
      selector: 'app-pipes',
      template: `    
        <p> {{usersName$ | async}}</p>
      `
    })
    export class MyComponent {
      usersName$: Observable<string>;
    }

Le pipe se charge de se désabonner de la source tout seul.
