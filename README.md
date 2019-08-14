# spg-website
Website for Snowy Pier Games LLC.

### Prerequisities
* [Node.js and npm](https://nodejs.org/en/)
* [Angular CLI](https://angular.io/cli)

### Building locally
```
cd spg-website
npm install
ng build
```
The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

Alternatively, if you're using Visual Studio as your TypeScript IDE, you can simply load the solution (spg-website.sln) into Visual Studio and then build it.

### Running locally
```
ng serve --open
```
The flag --open should open your browser to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Contributing
Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

This repo uses a feature branch workflow, as described [here](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow). Once a feature is ready to be merged into the master branch, please create a pull request.

### Running unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests
Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Help
For more help with Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
