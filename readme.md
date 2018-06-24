# CheatSheet

Dev notes I often need. Visit at [cheatSheet.software](http://cheatsheet.software).

## Node

### JSHint

In order to code in ES6 and tell this JShint, add a comment at the top of the file: `/* jshint esversion: 6 */` 

### JS, OOP and the sort

* [OOP in JS on Mozilla](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS)
* Very helpful: [The Object Explorer](https://sdras.github.io/object-explorer/) and [the Array Explorer](https://sdras.github.io/array-explorer/)
* About [Getter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get) and [Setter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set) on Mozilla.

### Logging with Winston

* [Getting Started Quickly With Node.js Logging, April 2018, Erik Dietrich](https://blog.scalyr.com/2018/04/getting-started-quickly-node-js-logging/)
* [The source of winston documentation: The winston Repo ;)](https://github.com/winstonjs/winston)

### Promises

* [A Simple Guide to ES6 Promises, Brandon Morelli, May 14 2018](https://codeburst.io/a-simple-guide-to-es6-promises-d71bacd2e13a): A very clear introduction to Promises. I read it many times - and will probably have to read it more often...
* [Returning Promise and/or callback](https://stackoverflow.com/questions/36837963/javascript-return-promise-and-or-call-callback): How to write a function that returns a promise and/or uses Callbacks
* [Node's promisify and callbackify](https://medium.com/trabe/understanding-nodes-promisify-and-callbackify-d2b04efde0e0)
* [Function decorators: Transforming callbacks into promises and back again, Joel Thoms, May 2017](https://hackernoon.com/transforming-callbacks-into-promises-and-back-again-e274c7cf7293): Explains how his own version of `promisify` and `callbackify` works.

### Files, writing / reading

* [How to write file if parent folder doesn't exist?](https://stackoverflow.com/questions/16316330/how-to-write-file-if-parent-folder-doesnt-exist) A thing I often needed...