==================
Main Differences
==================

Execution
++++++++++++++++++++++

**Python**

* Interpred

**Golang**

* Compiled



Object Orientation
++++++++++++++++++++++

**Python**

Python is very much like the traditional OOP languages. Python classes have every behaviour we are used to (inheritance, multiple inheritance, methods)

**Golang**

Go does not have classes, but instead, just like C we have structs and custom types

Static vs Dynamic
++++++++++++++++++++++

Python is a dynamic language and Go is a static language

**Python**

Python is dynamically typed::

   mystring = "Hej!"

**Golang**

Go is statically typed::

   var mystring string = "Hej!"

   or

   var mystring string
   mystring = "Hej!"

Concurreny
++++++++++++++++++++++

**Python**

Python has no builtin feature to do this, but the standard library provides many ways of doing it.

- Threads
- Processes
- Async

**Golang**

Goroutines are builtin and could be compared to threads (they are very different). They only exist in virtual space in go runtime.
To communicate between goroutines we use channels. They eliminate any race condition of shared memory.
