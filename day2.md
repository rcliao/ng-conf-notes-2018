# Day 2 Notes

## Reactive Testing

### Jest
* snapshot testing
    - Use snapshot to test `state` output for `reducer`
* `jest-preset-angular` library
* `jasmine-marbles` to test observables
    - e.g. `--a--b--|`

### Testing NgRX

#### Targets
* Dummy and smart components
* Reducers
* Side effects
* Selectors

## Jest testing
* snapshot testing

### Set up
* `npm i --save-dev jest-present-angular`

### Tips and trick
* `jest --watch`
* `jest --coverage`
* Use snapshot to test output (e.g. reducer state and component rendered output)
* Use `RxJS Marbles` to mock Observables

## VR Heroes
* Use `A-frame`
* Custom web component schema
* Use `| aframe` pipe to make Angular object works for a-frame

## Component Dev Kit
* Usage: Build your own component
* `npm i @angular/cdk`
* A bunch of utilities libraries to get common behaviors right
* https://github.com/EladBezalel/ngconf-cdk-workshop
