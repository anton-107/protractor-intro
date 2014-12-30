protractor-intro
================

Steps to run to install protractor on your machine:

Install nvm
-----------

1. install nvm ([instructions](https://github.com/creationix/nvm)) (OSX / Linux only)
2. create .nvmrc file in your project root with a node version number (i.e. "0.10")
3. cd to your project
4. nvm install
5. check that npm is using .nvm by running `which npm`


Install protractor
------------------

1. `npm install protractor -g` (installs protractor and webdriver-manager)
2. `webdriver-manager update` (installs selenium) 

Run protractor
--------------

1. `protactor tests/protractor.conf.js`


Debugging from within WebStorm
------------------------------
Read this useful short manual: http://ng-learn.org/2014/02/Debugging_Protractor_from_WebStorm_Intellij/
