# Design Patterns

Software design pattern is a general reusable solution to a commonly occurring problem within a given context in software design design patterns are formalized best practices that one can use to solve common problems when designing an application or system.

<hr/>

## 1. Null Object Pattern: 

* It is going to be used anytime when we have null object being returned so the keyword null.
* The idea behind the null object pattern is that you create an object that you return instead of null that has the exact same signature so the same properties and the same methods as the object we would already be returning from that method, and it will have default values for all these different properties and methods.
* This pattern is all about handling the null keyword in a way that removes all of those nasty if (object == null) checks from your code. 
* It also makes handling default values for null objects a breeze.

<hr/>

## 2. Builder Pattern:

* This pattern is useful when we need to create objects that have many different working parts that need to all come together to create one single object.
* Example: If we don't pass any of the value, we can default this to an empty js object and this just says if we only pass a name and nothing else just pretend that we passed an empty javascript object instead of nothing.
* It is one of the best creational design patterns for creating complex objects without complicating your constructors or code. 
* The best part about the builder pattern is that the new changes to JavaScript allow us to create extremely concise builders compared to the traditional way of creating builders.

<hr/>

## 3. Singleton Pattern:

* It is just a way of creating a single object that is shared amongst a bunch of different resources throughout your application without having to recreate that object or losing the information inside of it.

<hr/>

## 4. Facade Pattern:

* The idea of this is that we create a facade between our complex code and our actual business logic code that we are writing. 
* The idea of the facade pattern is to create your own API that hides away complex or repetitive code so that you are left with a clean and easy to use API. 
* The benefits of this is not only clean code that is easy and fun to work with, but your code is also much easier to refactor when the complex code behind your facade needs to change.

<hr/>

## 5. Command Pattern:

* The idea of the command pattern is to create an abstraction between the operations an object can do, its commands, and the actual commands themselves. 
* This makes it really easy to combine together or chain different commands without having to change the code. 
* The program can dynamically chain and combine these actions.
* The best part is since each command is its own object you can easily implement and undo function for each command and make a set of undo-able actions.

<hr/>

<hr/>

# SOLID DESIGN PRINCIPLES:

## 1. Single Responsibility Principle:

* The main idea of the single responsibility principle is that every class/function/module/section of your code should have only one responsibility. 
* This means that the code should only have one single reason to change. 
* If there are two different reasons for the code to change, or if it does two distinctly different things then it is in violation of this principle and is potentially poorly designed code.

<hr/>

## 2. Open/Closed Principle:

* The main idea of the open/closed principle is that every class/function/module/section of your code should be open for extension and closed for modification. 
* This means that a class/function/module should be able to be extended in functionality without having to go into the class and change it. 
* Essentially you shouldn't need to change existing code to add new functionality and instead should only have to add new code.

<hr/>

## 3. Liskov Substitution Principle:

* The main idea of the Liskov substitution principle is that any function/module that interacts with a class should also be able to interact with all subclasses of that class without breaking. 
* This essentially means that a class is interchangeable with its subclasses.

<hr/>

## 4. Interface Segregation Principle:

* The main idea of the interface segregation principle is that any class that implements an interface must use all functions/properties of the interface. 
* JavaScript does not have actual interfaces, but a class inheritance structure is similar enough that it works in this instance. 
* This means that any class that inherits from another class needs to use all of the methods/properties from the base class. 
* This encourages writing small classes instead of large classes.

<hr/>

## 5. Dependency Inversion Principle:

* The main idea of the dependency inversion principle is that any class that uses a dependency should only ever use the dependency through a predefined interface/wrapper. 
* This makes it so that your code will never directly depend on a low level API for its operations. 
* The reason this is so important is because if you ever need to change or remove that dependency it becomes really difficult when it is used all over your code. 
* By wrapping this dependency in an interface you can depend on the interface you created which will make changing out the dependency painless.
