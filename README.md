# Angular-Project---To-Do-List
A simple to do list web based app

Important commands <br>
<b>To see the version </b> $npm --version<br>
<b>Installing angular CLI globally, to generat eangular application anywhere on your machine</b> $sudo npm install -g @angular/cli<br>
<b>Creating angular application</b> $ng new Angular-Project--To-Do-List<br>
<b>Running the application</b>  $ng serve --open<br>
<b>Generating components (creating folders)</b>  $ng generate component components/todos<br>
<b>Generating components (alternative way - shorter)</b>  $ng g c components/ToDoItem<br>

Few things to note down <br>
1. New components has to be added in app.module.ts -> @NgModule -> declarations <br>
2. The selector mentioned in app.component.ts will be fetched in index.html <br>
3. In one template, you cannot have two root-items<br>
