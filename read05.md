http://localhost:3000/

web: node index.js

This declares a single process type, web, and the command needed to run it. The name web is important here. It declares that this process type will be attached to the HTTP routing stack of Heroku, and receive web traffic when deployed.
Heroku recognizes an app as Node.js by the existence of a package.json file in the root directory. For your own apps, you can create one by running npm init --yes.

The package.json file determines both the version of Node.js that will be used to run your application on Heroku, as well as the dependencies that should be installed with your application.

Once dependencies are installed, you will be ready to run your app locally. You’ll notice that a package-lock.json file is generated when npm install is run.
