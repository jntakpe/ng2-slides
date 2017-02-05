## Variables locales

    <input type="text" #name>
    {{ name.value }}
    
Référence l'objet *HTMLInputElement*.

    <input type="text" #name>
    <button (click)="name.focus()">Focus the input</button>

Marche aussi sur un webcomponent

    <google-youtube #player></google-youtube>
    <button (click)="player.play()">Play!</button>
