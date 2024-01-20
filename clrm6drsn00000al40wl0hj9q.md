---
title: "Building a Node server in 4 minute"
seoTitle: "Node server"
datePublished: Sat Jan 20 2024 14:39:05 GMT+0000 (Coordinated Universal Time)
cuid: clrm6drsn00000al40wl0hj9q
slug: building-a-node-server-in-4-minute
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1705761433314/f9ed6184-9e10-4750-b4d7-154d0fa2e061.jpeg
tags: javascript, nodejs, gdg, technical-writing-1, backend-developments

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1705748591455/00beb8a3-8120-47c7-b87b-2d24b341fe09.jpeg align="center")

Javascript is a very powerful programming language to work with reason being that it can be used to build our frontend application, Backend Application all at the same time. In this article, we will be building a Node server in two minutes.

**STEP1: DOWNLOADING AND INSTALLING NODE.JS.**

The first thing to do to get started is downloading node.js on our computer. Node.js is a javascript runtime environment. To download node.js visit the node.js official website https://node.js.com

**STEP2: CREATE A PROJECT FOR THE SERVE**R.

We create a folder for the server and give it a suitable name for the project. After creating the folder, navigate to your terminal and run the command;

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1705707536123/92bc9cdc-f6e7-475e-ba48-571717318a7d.jpeg align="center")

This command above will create a package.json file with its default settings;

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1705707758863/b5e2ef07-81a1-43de-a0a6-7bc72bf067a7.jpeg align="center")

This is a package.json file that contains the configuration of our javascript project. The file stores the name and version of our dependencies as well as other information about the dependencies.

**STEP3: INSTALL THE EXPRESS DEPENDENCY**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1705708663127/32df4136-2089-468d-aa35-d06ae8ad95ea.jpeg align="center")

after typing the command `npm install express` the express dependency will be added to the package.json file. We will also see a folder `node_modules`. The folder holds all the dependencies we will use for our Application. But you installed only one, why do you see so many? It is because Express itself requires some dependencies that require other dependencies.

**STEP4: WRITING OUR SERVER:**

After we have finished installing the express dependency, we create a file on our working directory. The name of the file can be `server.js`. We can use anything to name our file but it should be a javascript file.

let's start writing the code. from the file created `server.js` before we can use the express server, we will need to import express using the `require` function.

`const express = require("express")`

after importing it we create an instance of the application and set the port to 8000

`const app = express(),`

`const port 8000;`

after that, we create a route for the root URL (“/”) that sends the message "Welcome to my server"

`app.get('/', (req, res) => {   res.send('Welcome to my server!');   });`

Then finally we will start the server

``app.listen(port, () => {   console.log(`Server is running on port ${port}`);   });``

**STEP5: LAUNCHING THE SERVER:**

We will launch the server by locating our terminal and running the command;

`node server.js`

where server.js is the file name.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1705745239617/61e4add4-0527-41b4-a122-64514b999d76.jpeg align="center")

Congratulations we have built a Node server!!

Writing a backend server is not as difficult as people may perceive. Follow me to receive more of this Technical article