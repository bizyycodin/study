
8# Introduction
After reading this book I will be able to build my own applicaions in React. 

Explaining general concept, patterns, and best practices in a real world React application.

Detailed info on pagination, client-side caching and interactions such as searching and sorting.

I will write a Hacker News application tht interacts with a real world API.

Following best practices and patterns in React.

Write organized notes and commit to Github.

Dive into the ecosystem by bootstrpping my first React application from scratch with zero-configuration. Introduced to JSX and ReactDOM, prepare for my first React components.


#### Why am I learning React before Javascript?

- Because React implements Javascript, and while considering future developmental growth, learning both languages would take signifantly more time to learn all of javascript then all of React, in that order.

- React will challenge me, and then when I go to Javascript, a lot of what I will have completed, not only helps, but has similarites.


## node and npm


--- Flags ---

-g | globally.
-y | shortcut to initialize all defaults in package.json

--save-dev | indicates that the node package is only used in the development enviroment.
                          

node --version

npm --version

npm install

--- Install React ---

1. npm init -y (initializes npm project, and you must have this before you can install new local packages via npm.)

2. npm install react

3. creates folder called node_modules/ and will be listed in the package.json file next to your other dependencies.

 



You can share your project with other developers without sharing all the node packages. These packages are called dependencies. Everyone can copy your project without the dependencies. The dependencies are references in the package.json. 

Someone who copies your project can simply install all packages by using npm install on the command line.

The npm install script takes all dependencies listed in the package.json file and installs them in the node_modules/ folder.

npm install --save-dev <package>

It will not be used in production when you deploy your application on a server. 

What kind of node package could that be? Imagine you want to test your application with the help of a node package. You need to install that package via npm, but want to exclude it from your production environment. Testing should only happen during the devleopmental process but not when your application is already running in production.





--- Throwaway npm Project ---

1. Setup a throw away npm project

 2.1 Create a new folder with mkdir <folder_name>
 2.2 Navigate into the folder with cd <folder_name> 
 2.3 execute npm init -y or npm init 
 2.4 install a local package like React with npm install react
 2.5 have a look into the package.json file and the node_modules/ folder
 2.6 find out on your own how to uninstall the react node package again

3. read more about npm





--- Installation ---

The first one is to use a CDN.

CDN stands for Content Delivery Network.

CDN's host files publicly for people to consume them.

How to use a CDN to get started in React?

You can inline the <script> tag in your HTML that points to a CDN url. 

To get started in React you need to files (libraries): react and react-dom.


<script crossorigin src="https://unpkg.com/react@16/umd/react.development.js"> 
</\script>

<script crossorigin src="https://unpkg.com/react-din@16/umd/react-dom.developmen\t.js">
</script>


But why should you use a CDN when you have npm to install node packages such as React?

when your application has a package.json file, you can install react and react-dom from the command line. The requirement is that the folder is initialized as npm project by using npm itit -y with a package.json. You can install multiple node packages in one line with npm.

npm install react react-dom

--- Zero-Configuration Setup ---

npm install -g create-react-app

You can check the version of create-react-app to verify a successful installation on your command line:

create-react-app --version

Now you can bootstrap your first React application. We call it hackernews but you can choose a different name. The bootstrapping takes a couple of seconds. Afterward, simply navigate into the folder:

create-react-app hackernews
cd hackernews

Now you can open the application in your editor. The following folder structure, or a variation of it depending on the create-react-app version, should be pressented to you:

hackernews/
  README.md
  nodule_modules/
  package.json
   .gitignore
  public/
   favicon.ico
   index.html
   manifest.json 
src/
   App.css
 		 App.js
		 App.test.js
   index.css
   index.js
	  lovo.svg
	  registerServiceWorker.js

Here is a short break down of the folder and files. It is fine if you dont understand all of them in the beginning.

  README.md: The .md extension indicates that the file is a markdown file. Markdown is used as a lightweight markup language with plain text formatting syntax. Many source code projects come with a README.md file to give you iniitial instructions about the project. 




   



                         

















