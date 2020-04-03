# An Introduction to Node.js

**Node.js is a program we can use to execute JavaScript on our computers. In other words, it’s a JavaScript runtime.**

**use a version manager instead. This is a program that allows you to install multiple versions of Node and switch between them at will.
There are various advantages to using a version manager. For example, it negates potential permission issues when using Node with npm 
and lets you set a Node version on a per-project basis.**

* Node has excellent support for ECMAScript 2015 (ES6) and beyond. As you’re only targeting one runtime(a specific version of the V8 engine),
this means that you can write your JavaScript using the latest and most modern syntax.

* npm install -g jshint This will install the jshint package globally on your system

* We can also install packages locally to a project, as opposed to globally, on our system. Create a test folder and open a terminal in 
that directory. Next type this: npm init -y

* Node’s execution model causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous
connections.

**Node.js even has a built-in module to help you implement a cloning strategy on a single server.**

## What is the Downsides?
**The fact that Node runs in a single thread does impose some limitations. For example, blocking I/O calls should be avoided, 
CPU-intensive operations should be handed off to a worker thread, and errors should always be handled correctly for fear of crashing the
entire process.**

**Node is particularly suited to building applications that require some form of real-time interaction or collaboration — for example,
chat sites, or apps such as CodeShare, where you can watch a document being edited live by someone else.**

### With Node you can easily share code between the server and the client,meaning that when you’re working with Node, data can flow neatly
between layers without the need for reformatting. You can have one syntax from browser to server to database.

![image](https://s3-us-west-2.amazonaws.com/devcodepro/media/tutorials/instalacion-de-nodejs-en-ubuntu-t1.jpg)


