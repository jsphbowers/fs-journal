# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, Inheritance, and Polymorphism. 
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
property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is where code is broken down into smaller parts so that it is transferable and can be reintroduced into different sections and areas of code. It also helps to encourage privacy and making sure users cannot disrupt or break different parts of programs.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility principle where we want to keep our functions and operations down to one single responsibility that each function or operation is good at.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class describes a data type while an instance of a class is an object of that data type that exists  in memory.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is an object that stays in the place of the object that is needed to trigger a function or a trap in a function. It can oftentimes help change an object that is put in.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC pattern helps to create succinct segments of code that have special properties that help our code function properly. It also helps with security purposes where interactions between the user and the website become clearer and more secure where the user can't tamper with the inner parts of the code.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is the segment of code that interacts with the user and allows the user to make inputs that can then be prepared and exchanged and sent back to the user from the service.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The Service is placed to help make changes to the AppState and the memory within the code. It takes requests from the controller and makes those changes or denies them and then apply those changes and sends them back to the controller to display to the user.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is used in the MVC to help create the objects and how they are constructed within the program. It is a page where we can model a single instance so that we can create groups of objects that occur in the code and then manipulate them.
```
