# Sticky Datatable Header

A directive that can set a [PrimeNG Datatable](https://www.primefaces.org/primeng/#/datatable) header to sticky when scrolling the page. 
This feature prevents the header from scrolling with the table thus keeping the user in context and allowing data sort even when scrolled.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.5.

#Demo

A demo can be seen [here](https://amirch1.github.io/primeng-datatable-sticky-header).

#API

The directive accepts 2 attributes:

###stickyTop (number): Number of pixels from the window top after which the header becomes sticky. Default is 0.
###stickyClass (string): An optional class name that is added to the header when it is sticky allowing additional styling in sticky mode.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
