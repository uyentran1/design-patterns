## Suggestions for Object Oriented Design

Whenever writing code in an object oriented language, sticking to the following list of suggestions will make your code amenable to changes with the least effort.

* Separate out parts of code that vary or change from those that remain the same.
* Always code to an interface and not against a concrete implementation.
* Encapsulate behaviors as much as possible.
* Favor composition over inheritance. Inheritance can result in explosion of classes and also sometimes the base class is fitted with new functionality that isn't applicable to some of its derived classes.
* Interacting components within a system should be as loosely coupled as possible.
* Ideally, class design should inhibit modification and encourage extension.
* Using patterns in your day to day work, allows exchanging entire implementation concepts with other developers via shared pattern vocabulary.