nor-history.js
==============

[History.js](https://github.com/browserstate/history.js) NPM wrapper for easier 
use with browserify.

This repository does not contain any source code for History.js.

It declares a dependency for current History.js from Github. When you do 
`require('nor-history.js')` you will actually include 
`node_modules/history.js/scripts/bundled/html5/native.history.js`. 

***Please note:*** The actual version for History.js might be any 1.8.x even if 
this module lists the version as 1.8.0.

Installation
------------

You may install it from the NPM: `npm install nor-history.js`
