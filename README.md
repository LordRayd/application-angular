# ApplicationAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.2.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


# Export en Apk

## Commande a realiser
 * ng build --prod --aot
 * cordova build android
## Probleme rencontrer
*   Error occurred during initialization of VMCould not reserve enough space for 2097152KB object heap
    * Solution : re-télécharger un jdk 1.8 x32 et reparamétré JAVA_HOME
* Probleme de Path gradle
    * Download gradle et mettre le GRADLE_HOME à jour "C:\Program Files\Gradle\gradle-6.7\bin"
* Erreur de Licence
    * Executer "C:\Users\NOM\AppData\Local\Android\Sdk\tools\bin\sdkmanager" et accepter toutes les licences
    * Probleme lié au nouvelle version de gradle