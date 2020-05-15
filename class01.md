## Why would you want to run JavaScript code outside of a browser?

we can run Javascript outside a browser, just like build applications using Javascript.
All we need is to set up a Javascript platform such as NodeJS.

- Node.js is a platform for easily building fast, scalable network applications.
- This type of usage of javascript typically refers to backend programming where your javascript code will interact with your database and can be used to create RESTful APIs.
- Node.js makes building real-time apps lightning fast,
- Node.js makes coding in JavaScript for both the client and server side possible.
- Node.js increases the efficiency of the development process as it fills the gap between frontend and backend developers (more on this later).
- NPM gives developers multiple tools and modules to use, thus further boosting their productivity,
code executes faster than in any other language.

## What is the difference between a module and a package?
Module is a set of functions, globals and classes that you can import. Package is a set of modules.

## What does the node package manager do?
 NPM is a command line tool that installs, updates or uninstalls Node.js packages in your application.
 It consists of a command line client and an online database of public.

 ## Provide code snippets showing 3 different ways to export a function from a node module!
 1. require:

 ```javaScript
 {
 const fs = require('fs');
 }
 ```

2. exports:

```javaScript
 {

const printName = (name) => {
console.log(name);
};

exports.printName = printName;
}
 ```

3. module.exports:

```javaScript
 {

module.exports = {
  printName: (name) => {
  console.log(name);
  },
}
 ```

*Term*             |    *Documentation*
------------------ |    -----------
ecosystem          |    are large collections of software packages that depend on each other and co-evolve.
Node.js            |    JavaScript runtime built on Chrome's V8 JavaScript engine.
V8 Engine          |    Google's open source high-performance JavaScript and WebAssembly engine, written in C++. It is  used in Chrome and in Node.js
Module             |    Module is a set of functions, globals and classes that you can import.
package            |    Package is a set of modules.
npm                |    package manager for the JavaScript programming language.
server             |    server software dedicated to running this software, that can satisfy client requests on the World Wide Web.
environment        |    fundamental part of developing with Node. js, allowing your app to behave differently based on the environment you want them to run in.
interpreter        |    computer program that directly executes instructions written in a programming or scripting language, without requiring them previously to have been compiled into a machine language program.
compiler           |    a special program that processes statements written in a particular programming language and turns them into machine language or "code" that a computer's processor uses. 

### compiler vs interpreter
The main difference is that an interpreter directly executes the instructions in the source programming language while a compiler translates those instructions into efficient machine code. 

