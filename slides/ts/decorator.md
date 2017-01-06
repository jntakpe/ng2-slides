## Décorateurs

* Ajoutés à TypeScript pour Angular
* Permettent de modifier la cible
* Utilisés en Angular pour les metadonnées
* Proposés dans ES7

        @Component({selector: 'cpm-hello'])
        export class HelloComponent {
            @Input name: string;
            
            constructor() {
                console.log(`Hello ${name}`);
            }
        }
