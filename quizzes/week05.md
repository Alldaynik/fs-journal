# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
CRUD stands for Create Read Update and Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Post-create
Get -Read
Put - update
Delete- delete 
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM stand for Object Relational Mapping. we use it when we are creating relationships between different objects. there is a parent object and child object 
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
the create (post)
the update (put)

```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
synchronous
asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import mongoose from "mongoose"
let Schema = mongoose.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
middleware is the gate keeper between the server and the client. we can never trust the clients when they say who they are so we must provide credentials to verity that the client is actually that client 
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
CI
CL

```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
 async getAll(query = {winter}) {
    return await dbContext.Object.find(query)
  }
```