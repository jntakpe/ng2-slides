## Template validation   
   
        <h2>Sign up template form</h2>
        <form (ngSubmit)="register(loginForm.value)" #loginForm="ngForm">
         <div class="form-group">
           <label for="username">Nom d'utilisateur</label>
           <input type="text" class="form-control" id="username" name="username" placeholder="Nom d'utilisateur" ngModel required minlength="3">
         </div>
         <div class="form-group">
           <label for="password">Password</label>
           <input type="password" class="form-control" id="password" name="password" placeholder="Mot de passe" ngModel required>
         </div>
         <button type="submit" class="btn btn-success">Se connecter</button>
        </form>
