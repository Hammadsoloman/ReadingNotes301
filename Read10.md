# Call stack
## A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

* When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
* Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
* When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
* If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

**A call stack is used for several related purposes, but the main reason for having one is to keep track of the point to which each active subroutine should return control when it finishes executing. An active subroutine is one that has been called, but is yet to complete execution, after which control should be handed back to the point of call. Such activations of subroutines may be nested to any level (recursive as a special case), hence the stack structure.**

### The key takeaways from the call stack are:
1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.

![image](https://miro.medium.com/max/1400/1*7GXoHZiIUhlKuKGT22gHmA.png)


# How to Debug JavaScript Errors
**Debugging JavaScript errors in a production environment can be a difficult experience. More often than not, the error reports are vague, and identifying the underlying causes can be difficult at best. That said, there are a few common steps that can be followed towards identifying and resolving errors that crop up in production.**
#### Step 1: Attempt to replicate circumstances.
#### Step 2: Test assumptions
#### Step 3: Increase logging
#### Step 4: Adjust test parameters and try again

![image](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Debugging-and-Testing.png)

