## Template

    <div *ngIf="colors.length > 0">
      <h2>Colors</h2>
      <ul>
        <li *ngFor="let color of colors; let i = index;">{{i}} - {{color}}</li>
      </ul>
    </div>
