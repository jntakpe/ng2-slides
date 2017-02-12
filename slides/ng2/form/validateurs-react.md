## Réactive validation  
  
    @Component({
      selector: 'app-react-form',
      templateUrl: './react-form.component.html',
    })
    export class ReactFormComponent {
      loginForm: FormGroup;
    
      constructor(formBuilder: FormBuilder) {
        this.loginForm = formBuilder.group({
          username: formBuilder.control('', [Validators.required, Validators.minLength(3)]),
          password: formBuilder.control('', Validators.required)
        });
      }
    
      register() {
        console.log(this.loginForm.value);
      }
    }
