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

