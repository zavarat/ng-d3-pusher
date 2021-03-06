
# Angular 6 + Pusher + D3 - Real time Chart
<img src="./realtime-chart.gif"/>

## Mongod commands

```bash
mongod --dbpath D:\mg-data1 --replSet test1
mongo
use iotdb
db.createCollection('dooraccess')
rs.initiate()
```

## Angular CLI 

```bash
ng add @angular/material
npm install @angular/flex-layout --save
npm install d3 --save
ng add @angular/pwa
npm install --save-dev @types/d3
npm install --save hammerjs
```

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.5.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
