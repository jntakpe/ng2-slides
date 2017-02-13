## Récupérer des données

    @Injectable()
    export class GithubService {
    
      constructor(private http: Http) {
      }
    
      findReposForUser(username: string): Observable<any> {
        return this.http.get(`http://api.github.com/users/${username}/repos`);
      }
    }
