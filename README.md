# psbuiappangularfire2_nt


## 3. Installation and Setup
### 2 Firebase Fundamentals
```
ng server -o
```

```
ctrl shift `   launch cmd
```
```
npm install firebase angularfire2 --save
```

```
ctrl . fix formatting
```

install typescript importer

issue:Module not found: Error: Can't resolve 'promise-polyfill'
```
npm install promise-polyfill --save-exact
```
then we need to add database module in app.module.ts
[see here](https://stackoverflow.com/questions/43772474/no-provider-for-angularfiredatabase-angularfireauth/43772497#43772497)


### 5 Deploying to Firebase Hosting
```
npm i firebase-tools -g
npm install -g @google-cloud/functions-emulator
```
in the project folder
```
firebase login
firebase init
```
When asking
```
What do you want to use as your public directory?(public)  : dist
```
need to run all three choices.

#### 03:01
```
ng build --prod
firebase deploy
```

### 4 Adding Angular Material
```
npm i @angular/material @angular/animations @angular/flex-layout hammerjs --save
```

## 4. Retrieving and Working with Firebase Objects
angular2-switcher

### 6 Saving Objects
```
ng g c company/company-edit --spec false
ng g service company/company --spec false
```

### 9 Handling with Promises and Observables
```
import 'rxjs/add/observable/catch';  //personal testing failed.Instead, use
import 'rxjs/Rx';
```

```
ng g c company/company-list --spec false
```


### 3 Retriving Lists

```
ng g interface company
```

## 7. Authentication
### 2 Logging in Users
```
ng g service auth --spec false
```

### 4 Using Angular Guards to Secure Routes
```
ng g guard auth/auth --spec false
```
