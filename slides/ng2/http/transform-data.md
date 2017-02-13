## Transformer les données

Il faut tout d'abord importer l'opérateur *map* de RxJS.

    import 'rxjs/add/operator/map';

Puis nous pouvons transformer la réponse HTTP :

    findReposForUser(username: string): Observable<any> {
        return this.http.get(`http://api.github.com/users/${username}/repos`)
          .map(res => res.json());
      }
