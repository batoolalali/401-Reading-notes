## Advantages to Test Driven Development
1. Fast testing and fast Feedback.
2. reduces time spent on rework .
3. supports a clean interface.

## beforeEach() vs afterEach() in
beforeEach() is run before each test in a describe. (before initialize something)
afterEach() is run after each test in a describe.   (after clear somthing)

## The biggest downside is that if you really want to do TDD properly you will have to fail a lot before you succeed.

## is that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.

## static method
If you are writing utility classes and they are not supposed to be changed.

## Higher Order function

```JavaScript
{
let pushNumber = function(arr) {
  return arr.push(0);
};
}
```

if you decide you want to add zero to end of each array.

*Term*                   |    *Documentation*
-------------------------|    -----------
functional programming   |     is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects.
pure function            |     is a function where the return value is only determined by its input values, without observable side effects.
higher-order function    |     is a function that takes a functions as arguments or returns a function as its result.
immutable state          |     is state that cannot be changed 
object                   |     are containers for named values called properties or methods. 
oop                      |     is a programming paradigm based on the concept of "objects", which can contain data, in the form of fields, and code, in the form of procedures.
class                    |     is an extensible program-code-template for creating objects, providing initial values for state 
prototype                |     When a function is created in JavaScript, the JavaScript engine adds a prototype property to the function.
super                    |     keyword is used to access and call functions on an object's parent.
inheritance              |     Each object has a private property which holds a link to another object called its prototype. That prototype object has a prototype of its own, and so on until an object is reached with null as its prototype.
constructor              |     is a function that initializes an object. 
instance                 |     is the copy of the Reference that points to object at a point of time.
context                  |     is related to objects. It refers to the object to which a function belongs.
this                     |     this keyword refers to an object.
TDD                      |     is a software development process that relies on the repetition of a very short development cycle
jest                     |     JavaScript testing framework designed to ensure correctness of any JavaScript codebase.
CI                       |     is a software practice that requires frequently committing code to a shared repository.
unit test                |     is the process of testing the implemented code at a module level.