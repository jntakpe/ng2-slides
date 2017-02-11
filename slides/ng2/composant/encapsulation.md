## Encapsulation des composants

3 stratégies sont possibles:

* *ViewEncapsulation.Emulated* qui est la valeur par défaut
* *ViewEncapsulation.Native* qui s'appuie sur le *Shadow DOM*
* *ViewEncapsulation.None* qui désactive l'encapsulation


    @Component({
      selector: 'app-generated',
      templateUrl: './generated.component.html',
      styleUrls: ['./generated.component.css'],
      encapsulation: ViewEncapsulation.Native
    })

`Il est possible de cibler l'host avec le sélecteur *:host*`
