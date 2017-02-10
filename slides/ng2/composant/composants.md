# Composants

Il s'agit de directives avec des templates.

La déclaration du template peut se faire inline via l'attribut *template* ou via l'attribut *templateUrl* dans un fichier séparé.

    @Component({
      selector: 'app-generated',
      templateUrl: './generated.component.html',
    })
    export class GeneratedComponent implements OnInit {
    
      constructor() { }
    
      ngOnInit() {
      }
    
    }

`Grâce à Webpack le chemin absolu sera généré automatiquement`
