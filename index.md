---

theme : "night"
transition: "slide"
highlightTheme: "monokai"
# logoImg: "logo.png"
slideNumber: true
title: "MERN Introduction"

---

### MERN Introduction

<style>
pre {
  background: #303030;
  padding: 10px 16px;
  border-radius: 0.3em;
  counter-reset: line;
}
pre code[class*="="] .line {
  display: block;
  line-height: 1.8rem;
  font-size: 1em;
}
pre code[class*="="] .line:before {
  counter-increment: line;
  content: counter(line);
  display: inline-block;
  border-right: 3px solid #6ce26c !important;
  padding: 0 .5em;
  margin-right: .5em;
  color: #afafaf !important;
  width: 24px;
  text-align: right;
}

.reveal .slides > section > section {
  text-align:left; 
}

h1,h2,h3,h4 {
  text-align: center
}

p {
  text-align: center;
}

.present img {
    max-height: 65vh;
}
</style>

---

Yubin, Hsu

TSID / NTAP

ybhsu@tsmc.com

---

### Outline

- Web Application
  - 3-Tier Arch.
- MERN
  - What is MERN
  - MERN Arch.
  - MERN Component
  - Why MERN


---

### Web Application

--

not only a static website

---

### Web Application 3-Tier Arch.

- Frontend
- Backend
- Database

![](res/2021-11-21-12-08-11.png)

--

Frontend or Backend?

--

![](res/2021-11-21-12-10-59.png)

---

### What is MERN

--

A full-stack solution

---

### M.E.R.N. Component

- MongoDB - Database
- ~~Express~~ Fastify - Nodejs Web Framework
- React - client-side JavaScript library
- Node - JavaScript web server

--

### MERN Arch.

![](res/2021-11-21-12-29-32.png)

---

### React

- Open Source JavaScript Library
  - https://github.com/facebook/react
  - Maintained by Facebook
- Component-Based

--

![](res/2021-11-21-12-32-29.png)

--

Which of these frameworks would you like to keep on using or want to learn in the future?

![](res/2021-11-21-12-35-02.png)

https://tsh.io/state-of-frontend/

--

### Component-Based

- Build encapsulated component
  - Written in JavaScript instead of templates

--

![](res/2021-11-21-12-43-22.png)

---

### Node

--

- Node is a JavaScript runtime
  - Built on Chrome's V8 JavaScript engine
- Open Source
  - https://github.com/nodejs/node
- Cross Platform
  - Linux, Windows, MacOS, Docker Image, ...

--

![](res/2021-11-21-13-05-46.png)

--

Node Package Manager (NPM)

- Modules can be shared by packaging
- NPM is a package manager for node
  - Installed automatically with Node
  - Command Line Interface tool
  - Developer friendly
    - Manage all dependencies
    - Custom scripts

--

![](res/2021-11-21-13-10-08.png)

---

### Fastify

--

- Fast and low overhead web framework, for Node.js
- Highly performant

![](res/2021-11-21-13-36-15.png)

https://github.com/fastify/fastify

--

Define an endpoint example

![](res/2021-11-21-13-57-22.png)

--

Send a GET request to /ping

![](res/2021-11-21-14-01-22.png)

---

### MongoDB

--

Document Database

![](res/2021-11-21-14-04-30.png)

--

Schema Less

![](res/2021-11-21-14-07-47.png)

--

JavaScript Friendly
  - Use BSON internally

--

Issue of JSON for usage inside of a database

- JSON is a text-based format
  - Parsing slowly
- JSON's readable format is far from space efficient
- JSON only support a limited number of basic data types

--

BSON

- Binary JSON

![](res/2021-11-21-14-12-44.png)

- Developer use JSON as usual
https://subscription.packtpub.com/book/web_development/9781788624701/9/ch09lvl1sec53/json-versus-bson

---

### Mongoose

--

Mongoose is a MongoDB object modeling tool
  - Use official MongoDB driver as dependencies
  - Schema-Based

--

![](res/2021-11-21-14-18-24.png)

---

### Why MERN

--

JavaScript is popular

![](res/2021-11-21-14-23-11.png)

--

JavaScript Everywhere

![](res/2021-11-21-14-24-36.png)

--

JSON Everywhere

![](res/2021-11-21-14-26-28.png)

--

The npm Ecosystem

![](res/2021-11-21-14-30-40.png)

---

### If any question

--

![](res/2021-11-21-14-32-04.png)

--

![](res/2021-11-21-14-33-22.png)

---

### Weird JavaScript

--

![](res/2021-11-21-14-34-08.png)

--

![](res/2021-11-21-14-36-00.png)
https://www.freecodecamp.org/news/explaining-the-best-javascript-meme-i-have-ever-seen/

--

![](res/2021-11-21-14-37-13.png)

--

![](res/2021-11-21-14-37-42.png)

---

end