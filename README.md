# BootstrapIvyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.0-beta.11.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

## Project CMD
````
ng new bootstrap-ivy-app --enable-ivy --routing --skipInstall --skipTests --style=css
npm install --save
npm install --save-dev

````

## Project structure
```
src/                         project source code
|- app/                      app components
|  |- config/                config (configuration files)
|  |- core/                  core module (singleton services and single-use components - login,signup,dashboard)
|  |- shared/                shared module  (common components - footer,navbar,sidebar directives and pipes)
|  |- app.component.*        app root component (shell)
|  |- app.module.ts          app root module definition
|  |- app-routing.module.ts  app routes
```
cd src 
cd app
mkdir config

ng g c Home -sp false
ng g s Config --spec=false


ng g m shared
cd shared

ng g m components
cd components
    ng g c footer --sp false
    ng g c navbar --sp false
    ng g c sidebar --sp false
    
mkdir directive
mkdir models
mkdir pipes
mkdir service


ng g m core



```
├── src
│   ├── app
│   │   ├── app.component.css
│   │   ├── app.component.html
│   │   ├── app.component.spec.ts
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── app.routing.ts
│   │   ├── components
│   │   │   ├── components.module.ts
│   │   │   ├── footer
│   │   │   │   ├── footer.component.css
│   │   │   │   ├── footer.component.html
│   │   │   │   ├── footer.component.spec.ts
│   │   │   │   └── footer.component.ts
│   │   │   ├── navbar
│   │   │   │   ├── navbar.component.css
│   │   │   │   ├── navbar.component.html
│   │   │   │   ├── navbar.component.spec.ts
│   │   │   │   └── navbar.component.ts
│   │   │   └── sidebar
│   │   │       ├── sidebar.component.css
│   │   │       ├── sidebar.component.html
│   │   │       ├── sidebar.component.spec.ts
│   │   │       └── sidebar.component.ts
│   │   ├── dashboard
│   │   │   ├── dashboard.component.css
│   │   │   ├── dashboard.component.html
│   │   │   ├── dashboard.component.spec.ts
│   │   │   └── dashboard.component.ts
        |---layouts
│   │   │   └── admin-layout
│   │   │       ├── admin-layout.component.html
│   │   │       ├── admin-layout.component.scss
│   │   │       ├── admin-layout.component.spec.ts
│   │   │       ├── admin-layout.component.ts
│   │   │       ├── admin-layout.module.ts
│   │   │       └── admin-layout.routing.ts
│   │   │   └── blogs-layout
│   │   │       ├── blogs-layout.component.html
│   │   │       ├── blogs-layout.component.scss
│   │   │       ├── blogs-layout.component.spec.ts
│   │   │       ├── blogs-layout.component.ts
│   │   │       ├── blogs-layout.module.ts
│   │   │       └── blogs-layout.routing.ts
│   │   │   └── auth-layout
│   │   │       ├── auth-layout.component.html
│   │   │       └── auth-layout.component.ts
│
```
```
ng g cl my-new-class: add a class to your application
ng g c my-new-component: add a component to your 
ng g i my-new-interfaces: add a interfaces to your application
ng g d my-new-directive: add a directive to your application
ng g e my-new-enum: add an enum to your application
ng g m my-new-module: add a module to your application
ng g p my-new-pipe: add a pipe to your application
ng g s my-new-service: add a service to your application.
ng g g my-new-guards: add a guards to your application.
ng g s my-new-change-detection: add a change detection to your application.

# Generate directive 'component' without unit test
ng g s my-new-component: add a component to your application --spec=false
ng g c user-list --sp false

# To use inline html templates
ng g c user-list --inline-template

# Add module 'admin' with additional module containing routing information
ng g m admin --routing


#You can also combine flags listed above. For example, to create only .component.ts file without .css, .html, .spec files and folder use the following command.
$ ng g c user-list -f -it -is -sp false

# To enable folder creation add --flat false or -f false flag
$ ng g s user --flat false
ng g m guest -sp -r



```
ng g c Home -sp false


```javascript


```


https://clarity.design/documentation/get-started
