# educative.io

## Welcome to Angular

Angular comprises components, services, directives, modules, pipes, etc.

### The basic structure of an Angular application
 - NgModules
 - Components
 - Directives
 - Services and Dependency Injection
 - Routing
 - Data Binding

### Advantages of using SPAs
 - Easier to deploy in Production
 - Server to serve a minimum of 3 files — single-page index.html, a CSS bundle, and a JS bundle.
 - Faster page refreshes and no full-page refreshes occur.

#### Working with Angular CLI

##### Install NodeJS
 Verify NodeJS Version
```
 node -version OR node -v
```

When you install Node.js, it also installs the package manager npm. To check if npm is installed properly on your machine, use the command:

```
npm -version OR npm -v
```
#### Installing the Angular CLI
```
npm install -g @angular/cli
```

To check if Angular CLI is installed properly, use the command:
```
ng version OR ng v
```
The Angular CLI version#

To create a new Angular project 

```
ng new <project-name>
```

```
ng new angular-educative
```
To compile your application, use this command:

```
ng serve
```

Available CLI options#

```
--collection (-c)
    A collection of schematics to use in generating the initial app.
  --commit
    Initial git repository commit information.
  --create-application
    When true (the default), creates a new initial app project in the src folder of the new workspace. When false, creates an empty workspace with no initial app. You can then use the generate application command so that all apps are created in the projects folder.
  --defaults
    When true, disables interactive input prompts for options with a default.
  --directory
    The directory name to create the workspace in.
  --dry-run (-d)
    When true, runs through and reports activity without writing out results.
  --enable-ivy
    When true, creates a new app that uses the Ivy rendering engine.
  --force (-f)
    When true, forces overwriting of existing files.
  --help
    Shows a help message for this command in the console.
  --inline-style (-s)
    When true, includes styles inline in the component TS file. By default, an external styles file is created and referenced in the component TS file.
  --inline-template (-t)
    When true, includes template inline in the component TS file. By default, an external template file is created and referenced in the component TS file.
  --interactive
    When false, disables interactive input prompts.
  --minimal
    When true, creates a project without any testing frameworks. (Use for learning purposes only.)
  --new-project-root
    The path where new projects will be created, relative to the new workspace root.
  --prefix (-p)
    The prefix to apply to generated selectors for the initial project.
  --routing
    When true, generates a routing module for the initial project.
  --skip-git (-g)
    When true, does not initialize a git repository.
  --skip-install
    When true, does not install dependency packages.
  --skip-tests (-S)
    When true, does not generate "spec.ts" test files for the new project.
  --style
    The file extension or preprocessor to use for style files.
```

To look at the different options available, we can use the flag help:

ng help

```
ng new my-first-app
```

To create a component from the CLI, use:
```
ng generate component <component-name> OR ng g c <component-name>
```
We can create a directive in Angular by using the command:
```
ng generate directive <directive-name> OR ng g d <directive-name>
```

To create a service from the CLI, use the command:
```
ng generate service <service-name>
```
Compile the application:
```
ng serve
```
We can also create modules using the command:
```
ng generate module <module-name>
```

run angular with different port
```
ng serve --port 4400
```
test an Angular application
``
 ng test
``