## Réagir aux modifications

Grâce aux observables il est possible d'être notifié instantanément des changements.

     constructor(formBuilder: FormBuilder) {
        const isKnowUser = (control: FormControl) => ['jntakpe', 'gpeel'].filter(v => v === control.value).length ? null : {unknownUser: true};
        this.loginForm = formBuilder.group({
          username: formBuilder.control('', [Validators.required, Validators.minLength(3), isKnowUser]),
          password: formBuilder.control('', Validators.required)
        });
        this.loginForm.valueChanges.subscribe(form => console.log(form));
        this.loginForm.get('username').valueChanges.subscribe(username => console.log(username));
      }
