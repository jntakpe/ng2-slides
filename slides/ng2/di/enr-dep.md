Pour enregistrer une dépendance : 

    @NgModule({
      declarations: [],
      imports: [],
      providers: [GithubService],
      bootstrap: [AppComponent]
    })
    export class AppModule {
    }

Il est aussi possible de déclarer la dépendance directement sur le composant ciblé.

`Angular utilise plusieurs injecteurs cherchant les dépendances des enfants jusqu'au 'root injector'`
