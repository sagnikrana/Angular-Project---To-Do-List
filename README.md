# Angular-Project---To-Do-List
A simple to do list web based app

Important commands <br>
To see the version $npm --version
Installing angular CLI globally, to generat eangular application anywhere on your machine $sudo npm install -g @angular/cli
Creating angular application $ng new Angular-Project--To-Do-List
Running the application  $ng serve --open
Generating components (creating folders)  $ng generate component components/todos
Generating components (alternative way - shorter)  $ng g c components/ToDoItem

Few things to note down <br>
1. New components has to be added in app.module.ts -> @NgModule -> declarations <br>
2. The selector mentioned in app.component.ts will be fetched in index.html <br>
3. In one template, you cannot have two root-items<br>
