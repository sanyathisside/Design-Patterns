# Design-Patterns

Software design pattern is a general reusable solution to a commonly occurring problem within a given context in software design design patterns are formalized best practices that one can use to solve common problems when designing an application or system.

<hr/>

## 1. Null Object Pattern: 

* It is going to be used anytime when we have null object being returned so the keyword null.
* The idea behind the null object pattern is that you create an object that you return instead of null that has the exact same signature so the same properties and the same methods as the object we would already be returning from that method, and it will have default values for all these different properties and methods.

<hr/>

## 2. Builder Pattern:

* This pattern is useful when we need to create objects that have many different working parts that need to all come together to create one single object.
* Example: If we don't pass any of the value, we can default this to an empty js object and this just says if we only pass a name and nothing else just pretend that we passed an empty javascript object instead of nothing.

<hr/>

## 3. Singleton Pattern:

* It is just a way of creating a single object that is shared amongst a bunch of different resources throughout your application without having to recreate that object or losing the information inside of it.

<hr/>

## 4. Facade Pattern:

* The idea of this is that we create a facade between our complex code and our actual business logic code that we are writing. Not only it makes it so much easier to use these complex things but it also makes it really easy to replace it in the future.


