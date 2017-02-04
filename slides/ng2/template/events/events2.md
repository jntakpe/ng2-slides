Supporte aussi les événements bouillonnants

        <span (click)="toggleHide()">
          <button class="btn">Hide message</button>
        </span>
        
Il est possible de récupérer l'événement natif

        <button (click)="toggleHide($event)" class="btn">Hide message</button>

Mais aussi les événements clavier

        <input type="text" (keydown.space)="onSpacePress()">
