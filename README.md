
Install Angular-cli: npm install -g @angular/cli

Set up a new Sentry Angular project

Copy the DSN key from the Sentry Angular project and paste it in /src/app/app.modules.ts

Sentry.init({
    dsn: "<YOUR DSN GOES HERE>"
});
To start the dev server run ng serve

Navigate to http://localhost:4200/ to launch the application.

***If you get a "Cannot GET /" when you try to open the application on the browser, simply save your code again and let it recompile, this should fix it.
