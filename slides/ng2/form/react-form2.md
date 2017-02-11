
        
        @Component({
          selector: 'app-react-form',
          templateUrl: './react-form.component.html'
        })
        export class ReactFormComponent {
          loginForm: FormGroup;
          
          constructor(formBuilder: FormBuilder) {
            this.loginForm = formBuilder.group({username: '', password: ''});
          }
          
          register() {
            console.log(this.loginForm.value);
          }
        }

