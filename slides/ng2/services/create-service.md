## Créer ses services

Permet de partager des fonctionalités entre différents composants.

`Un service est une simple classe`

    export class GithubService {
      myRepos(): string[] {
        return ['ng2-todo', 'ng2-examples', 'ng2-slides'];
      }
    }
