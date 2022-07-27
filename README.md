# AngularMeanCrud

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

**angular component**

- npm install bootstrap

- set path style in augular.json "style" add path /Users/fr4nk/angular-mean-crud/node_modules/bootstrap/dist/css/bootstrap-reboot.min.css

- ng serve --open

- del code html but leave router-outlet

- create components add-book by command ng g c components/add-book

- create components add-book by command ng g c components/book-detail

- create components add-book by command ng g c components/books-list

- import { FormsModule, ReactiveFormsModule } from '@angular/forms';

  - import {HttpClientModule} from '@angular/common/http' in file app.module.ts and import within components @NgModule in Imports:[]

- add routing and set path in file app-routing.module.ts

**backend nodejs**

- create folder mkdir node-backend and initialize by command npm init

- install dependencie npm i express cors body-parser mongoose

- install nodemon for watch server npm i nodemon --save-dev

- create folder database and create file db.js mkdir database && cd database && touch db.js

- set path database mongodb

- create model schema by create folder model and file book.js code at file Book.js

- create route by create folder route and create file book.routes.js and crud method code at file

- create file index.js within backend folder for connect data base

- create file index.html in folder dist and set static directory path in index.js file

- set base route in index.js file

- defind path root of api and set port and listening server by port

- handler status error and 404

- start mongodb after install mongodb community macos use command brew services start mongodb-community
  Service `mongodb-community` already started, use `brew services restart mongodb-community` to restart.

- set nodemon on package.json and run server by npm start

**angular service**

- create crud service folder by command ng g s service/crud

  - import { catchError, map } from 'rxjs/operators';
  - import { Observable, throwError } from 'rxjs';
  - import { HttpClient, HttpHeaders, } from '@angular/common/http';

- create class for type Book

- create property api in class CrueService

- set http header in class CrueService

- create method crud in class CrueService

- craete method handlerError

- create navbar in file app.component.html by bootstrap
