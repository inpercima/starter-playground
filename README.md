# AngularCli

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.md)
[![dependencies Status](https://david-dm.org/inpercima/angular-cli/status.svg)](https://david-dm.org/inpercima/angular-cli)
[![devDependencies Status](https://david-dm.org/inpercima/angular-cli/dev-status.svg)](https://david-dm.org/inpercima/angular-cli?type=dev)

This project helps to understand and test the latest versions and plugins of angular and webpack in combination with angular-cli in order to integrate them into other projects.
It is only slightly adapted to preserve the structure but also to be able to map projects of the repositories of inpercima.

An update in this repository is always creating an new angular project to see the full changes per version.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.2.

I changed from npm to yarn with `ng config -g cli.packageManager yarn`.

## Prerequisites

### Angular CLI

* `angular-cli 13.0.2` or higher

### Node, npm or yarn

* `node 16.13.0` or higher in combination with
  * `npm 8.1.0` or higher or
  * `yarn 1.22.11` or higher, used in this repository

## Getting started

```bash
# clone project
git clone https://github.com/inpercima/angular-cli
cd angular-cli
```

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
