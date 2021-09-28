# javascript-question
### 1. What is call stack?
### 2. What's stored in a stack frame?
### 3. What is the role of the call stack?
### 4. What causes a stack overflow?

---
2. Local variables, 
Arguments passed into the method, 
Information about the caller's stack frame, 
The return address—what the program should do after the function returns (i.e.: where it should "return to"). This is usually somewhere in the middle of the caller's code.

### The key takeaways from the call stack are:
It is single-threaded, Meaning it can only do one thing at a time. 
Code execution is synchronous.
A function invocation creates a stack frame that occupies a temporary memory. 
It works as a LIFO — Last In, First Out data structure.
---
[Value Types and Reference Types] (https://gist.github.com/branneman/7fb06d8a74d7e6d4cbcf75c50fec599c)
