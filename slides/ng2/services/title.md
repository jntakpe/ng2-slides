## Title

Ce service permet de modifier le titre d'une page HTML

    @Component({
      selector: 'app-github',
      templateUrl: './github.component.html',
      styleUrls: ['./github.component.css']
    })
    export class GithubComponent implements OnInit {
    
      repos$: Observable<string[]>;
    
      constructor(title: Title) {
        title.setTitle("Github component");
      }
    }
