## Angular Unit Testing Introduction


Taken from [Smashing magazines introduction to unit testing with Angular](http://www.smashingmagazine.com/2014/10/07/introduction-to-unit-testing-in-angularjs/). I copied the code from [their GitHub](https://github.com/lorem--ipsum/smashing-article).


### Why 

Getting into unit testing with AngularJS.



### Tools Used

- [Karma](http://karma-runner.github.io/0.12/index.html) test runner
- [Chai](http://chaijs.com/) assertion library
- [Sinon](http://sinonjs.org/) library for stubbing and mocking external dependencies 
- [Mocha](http://mochajs.org/) test framework

Mocha is said to be superior for asynchronous testing compared to alternative javascript testing frameworks like [Jasmine](). The issue is debated in this [article](http://www.techtalkdc.com/which-javascript-test-library-should-you-use-qunit-vs-jasmine-vs-mocha/).

Other tutorials covering the same testing stack are [attackofzach.com](http://attackofzach.com/setting-up-a-project-using-karma-with-mocha-and-chai/) and [blog.codeship.com](http://blog.codeship.com/mocha-js-chai-sinon-frontend-javascript-code-testing-tutorial/).


### NPM Modules Used

- karma-coverage
- karma-mocha
- karma-phantomjs-launcher
- karma-sinon-chai
- mocha


### Using the App

- clone the repository
- bower install
- npm install
- npm install -g karma-cli

Test that Karma is installed ok by entering:
<pre>karma --version</pre>

The code comes with a Karma configuration file _karma.conf.js_. You could have created a new configuration file by doing: 
<pre>karma init</pre>


#### Run the tests by entering:

- karma start karma.conf 
- browse to _http://localhost:9873/_
- The result of the tests will appear in the console
