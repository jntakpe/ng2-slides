# Interpolation

* Affichage de valeurs dans un template
* Syntaxe moustache/double curly braces

        import {Component} from '@angular/core';
        @Component({
          selector: 'app-interpolation',
          template: `
            <h1>{{titre}}</h1>
          `
        })
        export class InterpolationComponent {
          titre: string = 'Interpolation';
        }
