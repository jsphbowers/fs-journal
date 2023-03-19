# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```

```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
The event listener is a line of code that "listens" to other pages in javascript and invokes a function whenever there is a change to the segment of code that is being "listened" to.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
O-pen closed Principle. This principle is the concept that when we create a function or class or part of code it needs to be open and closed so that if we want to modify or make changes then we should not have to go back in and change the original or "old" code.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
Callbacks are where we take a function and it sends out a "messenger" to get data and bring it back to the original caller or higher order function. When that data comes back to the higher order function then it is complete.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise function has to do with async functions where the logical part of the function makes a "promise" to return with certain information and if that promise is broken it sends an error. Typically in the form of an HTTP error. We can capture this error with a "try-catch" function where if there is an error we console log it to our screen for developers and if we want to we can also call a function that displays it for the user.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Put, Get, and Delete.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application programming interface.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service is in charge of making calls.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation is helpful in keeping alignment with the SOLID principles where everything within a program has a specific function that it serves and we do not get crossover or confusion within the program. It also helps to keep things readable and usable as well as make things more accessible for other users. It also helps with security and ensuring that users cannot manipulate or have access to data they shouldn't.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200 is a successful request.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
500 is an internal server error.
```