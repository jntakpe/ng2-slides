## NgSwitch

Permet de choisir entre plusieurs possibilités

    <div [ngSwitch]="messageCount">
      <p *ngSwitchCase="0">You have no message</p>
      <p *ngSwitchCase="1">You have a message</p>
      <p *ngSwitchDefault>You have some messages</p>
    </div>

