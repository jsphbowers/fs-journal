# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create, Read, Update, Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Create corresponds to Post which lets you create an object in an api.
Read corresponds to Get which allows you to read the contents of an api and pull content.
Update corresponds to Put which allows you to pull a specific object from an api and update it.
Delete corresponds to delete which can be used to remove objects from an api.
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object Relational Mapping, we use mapping for when we are pushing data up to MongoDB and when we are pulling it down in order that it will match out data in our servers and also on our front side with Node.js
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
Put and Post as one is used to update an api and the other is used to create a new object within an api.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
synchronous and asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import mongoose from "mongoose"
let Schema = 
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is software that is used to help with authentification and making sure the user who is on the account is the actual user who is making changes to the page.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
continuous integration and continuous delivery
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
http://?winter
```