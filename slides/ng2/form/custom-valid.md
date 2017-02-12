## Validation custom

    export class ValidFormComponent {
    
      loginForm: FormGroup;
    
      constructor(formBuilder: FormBuilder) {
        const isKnowUser = (control: FormControl) => ['jntakpe', 'gpeel'].filter(v => v === control.value).length ? null : {unknownUser: true};
        this.loginForm = formBuilder.group({
          username: formBuilder.control('', [Validators.required, Validators.minLength(3), isKnowUser]),
          password: formBuilder.control('', Validators.required)
        });
      }
    }

Si la fonction renvoie un observable la validation deviendra asynchrone.
