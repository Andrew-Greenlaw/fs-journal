# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
create,read,update,and delete.
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
create corresponds with post and read is with get, update is with the put, and delete is also delete
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
object relational mapping, its where objects are used to connect the programing to the database system and we use auth0 with the mongoose to make sure its secure and everything.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
the put and the post have a body. or in otherwords pass formdata to be used.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
asyncronous coding model.
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
mongoose from mongoose and mongoose.Schema
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
middleware are the little security checkpoints that make sure you are not getting bad dudes or dumb duded. and is the bridge from the server side to the client side.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
request pipeline and the response pipline
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
GET ?tag=winter
```