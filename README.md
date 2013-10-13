test.it - node.js
===================

node.js output module for test.it framework

## Install
+ First: install framework and output module
    ```bash
npm install 'test.it'
npm install 'test.it-nodejs'
    ```
    **Hint:** *you can use [`-g`](https://npmjs.org/doc/install.html) flag to install them globally*
+ Second: add core of framework and output module, set it as default printer
    ```javascript
test = require('test.it');
nodeConsole = require('test.it-nodejs');
test.printer(nodeConsole);
    ```
    btw you can use this construction:
    ```javascript
(test = require('test.it')).printer(require('test.it-nodejs'));
    ```
    **Info:** *Output module is not required!*

## Example
![console](https://f.cloud.github.com/assets/3748976/1114018/937bf36e-1a0d-11e3-8a37-5450efca4362.png)
