# YogeCode

To Create Project Run `ng new project_name`

1. ng new installs the necessary npm packages and other dependencies that Angular requires. This can take a few minutes.
2. ng new also creates the following workspace and starter project files:
   -> A new workspace, with a root directory named angular-tour-of-heroes
   -> An initial skeleton application project in the src/app subdirectory Related configuration files

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.10.

## Development server

Run `ng serve --open` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Angular components

- Components are the main building blocks for Angular applications. Each component consists of:
  - An HTML template that declares what renders on the page
  - A TypeScript class that defines behavior
  - A CSS selector that defines how the component is used in a template
  - Optionally, CSS styles applied to the template

#### Creating a component using the Angular CLI

- From a terminal window, navigate to the directory containing your application
- Run the ng generate component <component-name> command, where <component-name> is the name of your new component.
- By default, this command creates the following:
  - A directory named after the component
  - A component file, <component-name>.component.ts
  - A template file, <component-name>.component.html
  - A CSS file, <component-name>.component.css
  - A testing specification file, <component-name>.component.spec.ts

#### Introduction to components and templates

- A _component controls_ a patch of screen called a view. It consists of a _TypeScript class_, an _HTML template_, and a _CSS style sheet_. The TypeScript class defines the interaction of the HTML template and the rendered DOM structure, while the style sheet describes its appearance.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
