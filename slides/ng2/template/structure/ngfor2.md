Variables supplémentaires :

* index
* even
* odd
* first
* last


    <ul>
      <li *ngFor="let color of colors; let i = index">{{i}} - {{color}}</li>
    </ul>
