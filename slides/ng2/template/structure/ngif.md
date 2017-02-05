## NgIf

Version standard

    <template [ngIf]="colors.length > 0">
        <div><h2>Colors</h2></div>
    </template>

Version courte

    <div *ngIf="colors.length > 0">
        <h2>Colors</h2>
    </div>

