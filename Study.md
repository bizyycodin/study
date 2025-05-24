# Introduction
After reading this book I will be able to build my own applicaions in React. 

Explaining general concept, patterns, and best practices in a real world React application.

Detailed info on pagination, client-side caching and interactions such as searching and sorting.

I will write a Hacker News application tht interacts with a real world API.

Following best practices and patterns in React.

Write organized notes and commit to Github.

Dive into the ecosystem by bootstrpping my first React application from scratch with zero-configuration. Introduced to JSX and ReactDOM, prepare for my first React components.


#### Why am I learning React before Javascript?

- Because React implements Javascript, and when thinking of efficiency purposes, learning both languages would take signifantly more time to learn all of javascript then all of React, in order.

- React will challenge me, and then when i go to Javascript, a lot of what i did will not only help, but have similarites.


## node and npm


--- Flags ---

-g | globally.
-y | shortcut to initialize all defaults in package.json

--save-dev | indicates that the node package is only used in the development enviroment
                          

node --version

npm --version

npm install

--- Install React ---

1. npm init -y (initializes npm project, and you must have this before you can install new local packages via npm.)

2. npm install react

3. creates folder called node_modules/ and will be listed in the package.json file next to your other dependencies.


You can share your project with other developers without sharing all the node packages. These packages are called dependencies. Everyone can cpy your project without the dependencies. The dependencies are references in the package.json. 

Someone who copies your project can simply install all packages by using npm install on the command line.

The npm install script takes all dependencies listed in the package.json file and installs them in the node_modules/ folder.

npm install --save-dev <package>

It will not be used in production when you deploy your application on a server. 

What kind of node package could that be? Imagine you want to test your applicatoin with the help of a node package. You need to install that package via npm, but want to exlcude it from your production environment. Testing should only happen during the devleopmental process but not when your application is already running in production.

                         












