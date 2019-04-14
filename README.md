# react_with-node.js
sample create react app with nodejs

1- require node.js

2- Create a React project - 
  mkdir react
  cd react
  npx create-react-app  hello-react
	//creates react project folder contents
	
3. run project
        cd hello-react
        npm start
    runs dev server on http://localhost:3000/
		
4. project folder contents - The package.json file tells you what libraries you are using and their versions. It also contains other information such as application name, your application version and commands to run applications, build applications

	The  package.json file is very important. If a new library needs adding to your project, please declare its name and version in this file.  After that, execute the  "npm install" command, this library shall be downloaded to the  node_modules directory for you. You also can delete all in the  node_modules directory and execute the   "npm install" command to download all libraries again.

  5. App.js & App.css both inside src on your browser and delete all their contents.
