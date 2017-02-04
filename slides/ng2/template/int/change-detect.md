## Change detection

    import {Component} from '@angular/core';
    @Component({
      selector: 'app-change-detect',
      template: `
        <h1>Change detection</h1>
        <h2>{{seconds}} s depuis le chargement</h2>
      `
    })
    export class ChangeDetectComponent {
      seconds = 0;
      constructor() {
        setInterval(() => this.seconds++, 1000);
      }
    }
