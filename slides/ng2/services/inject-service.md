## Injecter des dépendances

Pour injecter des dépendances dans un service, il faut l'annoter de *Injectable()*.

    @Injectable()
    export class GithubService {
    
      constructor(private http: Http) {
      }
    
      findReposForUser(username: string): Observable<any> {
        return this.http.get(`http://api.github.com/users/${username}/repos`)
          .map(res => res.json());
      }
    }
