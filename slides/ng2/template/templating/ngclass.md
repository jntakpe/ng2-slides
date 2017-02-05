## NgClass

Permet d'ajouter dynamiquement des classes sur un élément

    <button [class.btn-success]="isSuccess()">Success or not ?</div>

    <button [ngClass]="{'btn-success': isSuccess(), 'btn-image': hasImage()}">Success</button>
