testit-nodejs
===================

node.js output module for [testit](https://github.com/titulus/testit) framework

## Install
+ First: install framework and output module
    ```bash
npm install 'testit'
npm install 'testit-nodejs'
    ```

    **Hint:** *you can use [`-g`](https://npmjs.org/doc/install.html) flag to install them globally*
+ Second: add core of framework and output module, set it as default printer
    ```javascript
test = require('testit');
nodeConsole = require('testit-nodejs');
test.printer(nodeConsole);
    ```
    btw you can use this construction:
    ```javascript
(test = require('testit')).printer(require('testit-nodejs'));
    ```
    
    **Info:** *Output module is not required! You can use testit without any output at all.*

## Example
![console](https://f.cloud.github.com/assets/3748976/1114018/937bf36e-1a0d-11e3-8a37-5450efca4362.png)
