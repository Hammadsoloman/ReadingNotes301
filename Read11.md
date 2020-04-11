# Express.js
#### is a web application framework for Node.js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.js.
## Express and middleware
### Express is a framework based on middleware, which are application modules each providing a specific feature. You can decide which middleware you want to load. 
#### Express comes with over 15 basic pieces of middleware, and of course developers can add others via NPM. Each piece of middleware provides a micro-feature. Here are a few examples:
* compression: enables for gzip compression of pages for faster sending to the server.
* cookie-parser: allows you to work with cookies.
* cookie-session: allows you to generate session information (during a visitor’s stay on the website).
* serve-static: allows the return of static files contained in a folder (images, files to download, etc).
* serve-favicon: manages your website's favicon.
* csrf: provides protection against CSRF faults.
* etc.

**All these middleware offer micro-features: some of them are really small, like "serve-favicon" for example.**
**These pieces of middleware are interconnected and can communicate with each other. Express simply adds the routes and views above the whole thing.**

All these pieces of middleware communicate with each other by sending up to 4 settings:
* err: errors.
* req: the visitor’s request.
* res: a response to return (the HTML page and the header information).
* next: a callback to the next function to be called.

### Summing up:
* Express.js is a micro-framework for Node.js. The most common tasks are therefore greatly simplified.
* Express specifically allows the simple management of routes (the different URLs accepted by your app).
* Express provides a bridge between template engines (such as EJS). These allow us to separate occupational code (backend) from HTML code (frontend). This spells the end for lengthywrite()  calls.
* Express is based on middleware, which are mini-layer applications that offer features such as sessions, gzip page compression, cookie handling, etc.

![image](https://i1.wp.com/barreto.io/wp-content/uploads/2018/03/maxresdefault-banner.jpg?w=1740)
