# Anguloffee - AngularJS with CoffeeScript starter

This project is an application skeleton for a typical
[AngularJS](http://angularjs.org/) web app with
[CoffeeScript](http://coffeescript.org) similar to
[angular-seed](https://github.com/angular/angular-seed).

[![forthebadge](http://forthebadge.com/badges/built-with-love.svg)](http://forthebadge.com)

## Anguloffee has:

* Support for CoffeeScript
* Up-to-date dependencies (Angular, Jasmine, Karma)
* [PhantomJS](http://phantomjs.org/) as default environment for running unit
  tests instead of Chrome. That gives you ability to test your application also
  in cloud based IDE like Cloud9.
* Task runner agnostic approach. Use Gulp, Grunt, Broccoli, Cake or whatever
  else which suits you best!
* Cool name. AngularJS + Coffee = Anguloffee. That's funny..., right?

## Weird stuff:

* **app/lib?** Keep there libraries which cannot be installed via brower e. g.
  customized version of Modernizr.
* **jQuery dependency?** Yeah! You probably don't need it in your app but it comes
  in handy when unit testing.

## Instalation

To get Anguloffee working run:

```
npm install
bower install
```

If you don't have `karma-cli` installed yet you should do it in order to run
tests. Http server is optional.

```
npm install -g karma-cli
npm install -g http-server
```

To run E2E test you'll need [Protractor](http://angular.github.io/protractor/):

```
npm install -g protractor
```