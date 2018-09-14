# \<people-list\>

Polymer 2 exercise

- Build a component which show a list of people showing first name, last name and age.
- At the bottom of the list, show the age average for all people in the list.
- Each item in the list must have a color depending on age
  - #fffff if equal or less than 19 yo.
  - #e1f5fe if greater than 19 yo.
  - #b3e5fc if greater than 29 yo.
  - #e1f5fe if greater than 39 yo.
- Include a form with fields first name, last name and age to add a new person to the list.

## Requisites
Make sure you have the following installed in your machine:
- [Node.js](https://nodejs.org) and npm - How to install with nvm [here](https://github.com/creationix/nvm#installation)
- [Polymer CLI] (https://github.com/Polymer/tools/tree/master/packages/cli)

## Viewing the application

```
$ polymer serve
```

## Building the application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

You can run the tests directly on your browser, just run `$ polymer serve` and navigate to http://localhost:8081/test

## TO-DO

- [ ] Chore: Add coverture to tests -
    *Need to investigate deeper with [web-components-tester-istambul](https://github.com/thedeeno/web-component-tester-istanbul). See issues [6](https://github.com/thedeeno/web-component-tester-istanbul/issues/6) and [9](https://github.com/thedeeno/web-component-tester-istanbul/issues/9)*
- [x] ~~Feature: Integrate Firebase~~
- [x] ~~Feature: Place form into a dialog~~
- [ ] Feature: Remove person from people list
- [ ] Feature: Edit person

## Nice to have
- Sortable list by people fields
