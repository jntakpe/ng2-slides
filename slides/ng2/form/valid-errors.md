## Affichage des erreurs

          <div class="form-group" [ngClass]="{'has-danger': loginForm.get('password').touched && loginForm.get('password').invalid}">
            <label for="password" class="form-control-label">Password</label>
            <input class="form-control" [ngClass]="{'form-control-danger': loginForm.get('password').touched && loginForm.get('password').invalid}"
                   type="password" id="password" placeholder="Mot de passe" formControlName="password">
            <div class="form-control-feedback" *ngIf="loginForm.get('password').touched && loginForm.get('password').hasError('required')">
              Le mot passe est obligatoire
            </div>
          </div>
          <button type="submit" class="btn btn-success" [disabled]="loginForm.invalid">Se connecter</button>
