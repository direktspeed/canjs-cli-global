@page DoneJS
@hide title
@hide sidebar

![DoneJS logo](https://donejs.com/static/img/donejs-logo-black.svg)

[![npm version](https://badge.fury.io/js/donejs.svg)](https://badge.fury.io/js/donejs)
[![Build Status](https://travis-ci.org/donejs/donejs.svg?branch=master)](https://travis-ci.org/donejs/donejs)
[![Build Status](https://ci.appveyor.com/api/projects/status/github/donejs/donejs?branch=master&svg=true)](https://ci.appveyor.com/project/daffl/donejs)
[![Coverage Status](https://coveralls.io/repos/github/donejs/donejs/badge.svg?branch=cli-refactor)](https://coveralls.io/github/donejs/donejs?branch=master)

DoneJS is the easiest way to get a high performance, real time, web and mobile application
done! The framework provides a nearly comprehensive combination of technologies for
building complex JavaScript applications.

If you are looking for the fastest way to get a fully modern development environment setup
and produce a lightning fast application, you've come to the right place.

DoneJS is a combination of the following technologies:

- [StealJS](http://stealjs.com) - ES6, CJS, and AMD module loader and builder
- [CanJS](https://canjs.com) - Custom elements and model-view-viewmodel (MVVM) utilities
- [jQuery](https://jquery.com/) - DOM helpers
- [jQuery++](http://jquerypp.com) - Extended DOM helpers
- [QUnit](https://qunitjs.com/) or [Mocha](https://mochajs.org/) - Assertion library
- [FuncUnit](https://funcunit.com/) - Functional tests
- [Testee](https://github.com/bitovi/testee) or [Karma](https://karma-runner.github.io/) - Test runner
- [DocumentJS](http://documentjs.com) - Documentation
- [can-ssr](https://github.com/canjs/ssr) - Server-side rendering utilities for CanJS

DoneJS is a `npm` package that simply installs all the previous
technologies.  This site exists to explain the collective benefits of these technologies
and provides a [Guide guide] for using them together to build an "amazing" application.


### Features ([Features main article])

[![Greenkeeper badge](https://badges.greenkeeper.io/direktspeed/canjs-cli-global.svg)](https://greenkeeper.io/)

_Application features:_

- Isomorphic (same code on server and client).
- Pushstate routing
- Real time
- Run everywhere ( IE9+, Android, iOS, node-webkit )

_Performance features:_

- Progressive loaded optimized production builds
- Caching and minimal data requests
- Minimal DOM updates
- Application logic in worker thread

_Maintenance features:_

- Modlet workflow - tests, docs, and demo pages
- Use and create NPM packages
- Custom HTML elements
- MVVM single direction architecture
- Multi-versioned documentation
- Hot module swapping
- Functional tests



#### Getting Started Guide ([Guide main article])

The DoneJS Getting Started Guide walks you through creating a [PlaceMyOrder](http://place-my-order.com) application.

1. Install
   1. Set up server
   2. Set up client
2. Setting up server side rendering
   1. Create the main template
   2. [Create the application view model](docs/getting_started_outline.md#create-the-application-view-model)
   3. Render the main template on the server
   4. [Start the server](docs/getting_started_outline.md#start-the-server)
3. Setting up routing
   1. Create routes
   2. Create a homepage element
   3. Create a restaurant list element
   4. Switch between pages
   5. Create a header element
   6. Create a order history element
   7. Switch between three pages
4. Getting data from the server and showing it in the page.
5. Creating a unit-tested view model and demo page
   1. Identify the view model state properties
   2. Test the view model
      1. Setup the test
      2. Create fake data
      3. Use fake data for ajax requests
      4. Create a view model instance and test its behavior
   3. Write the view model
      1. Make dependent models
      2. Define stateful property behaviors
      3. Verify the test
   4. Create a demo page
   5. Write the template
      1. Verify the demo page and application works.
6. Setup continuous integration (CI) and tests.
6. Nested routes
7. Importing other projects
8. Creating data
9. Setup up a real-time connection
10. Production builds
    1. Bundling your app
    2. Building to iOS and Android
    3. Building to NW.js
11. Deploying
