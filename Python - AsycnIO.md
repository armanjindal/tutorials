**AsyncIO?**
---
- Python library used to write concurrent code 
- **Concurrent** programs can run means it could run at the same time but not necessarily
	- Work using **async/await** syntax
- Used for I/O bound and high-level structured network code. 
- For CPU bound use the *multiprocesing* library 

- Allows code to fire multiple requests into EVENT-LOOP, block a specific function (called a coroutine) untill the I/O request is completed, then tells Python 

Generators - something in Python that creates a sequence of values
	- list(generator) - exhuasts the generator by calling next on it untill it is exhuasted and puts it into a list. 

Co-routines - Similar to generators as both can be used to stoped/pause executetion. Co-routines **consume** data while generators produce them. 

Await - used prior to async operations. Like break points which pause execution of following code (in the scope) untill the asynchronous call has been returned. 

Event Loop - Core of an async app. Run async tasks, callbacks and  I/Os 

Aynchronous Generators: 
	- When you are making a series of calls to databases/APIs and you do not know how long it is going to take. You want to service them and process the data ASAP. 

Def CallBack -  a callback is a function that gets passed into another function as an argument where it’s executed when the parent function wants it to be executed. Immediatley in the case of synchronous function and whenever in an async one. 
