# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
abract, encapsulation, inheritance, and polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
encapsulation is usually used to hide data making it private and expose public property. and do hide methods so people cant access certain things and mess everything up.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsibility, this means that every class or module has one purpose and functionallity to break up you code in small spurts of done.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
a class will always be there but you need a instance in order to use the methods in the class. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
a proxy object is a wat to change the functionality of a normal object to where the proxy acts like a link to the object for the client only if it is accessable.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
to organize and structure you code better. allowing you to have more functionality in you code.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
the controller is what interacts directly with the DOM and controlls where the data will go either to be stored grabed or changed.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
the service is the changing of data and where all of the manipulation functions go so that we can directly work with the appstate.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
the model is the bluprints and recipe for our data and how it need to be stored and accessed properly. it works directly with all the stored data in the appstate.
```
