test.it - node.js
===================

node.js output module for test.it framework

## Install
```
# install core if you don't done it yet
npm install test.it

# install nodejs output module
npm install test.it-nodejs
```

## Preparation
Include testit core and output module. Make it a default printer.
```javascript
test = require('test.it'); // include core
output = require('test.it-nodejs'); // include output
test.printer(output); // change default printer
```
or shorter
```javascript
(test = require('test.it')).printer(require('test.it-nodejs'));
```
Test!

## Example
![console](https://f.cloud.github.com/assets/3748976/1114018/937bf36e-1a0d-11e3-8a37-5450efca4362.png)
