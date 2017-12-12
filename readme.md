GIT ORIGINAL:

	…or create a new repository on the command line

	echo "# MeanStackCRUDApp-Angular4" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/lmarcela/MeanStackCRUDApp-Angular4.git
	git push -u origin master
	…or push an existing repository from the command line

	git remote add origin https://github.com/lmarcela/MeanStackCRUDApp-Angular4.git
	git push -u origin master
	…or import code from another repository
	You can initialize this repository with code from a Subversion, Mercurial, or TFS project.



en la carpeta ExpressServer:

1. npm init
   creo archivo package.json:
   {
  "name": "express-server",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "marcela",
  "license": "ISC"
}

2. npm install express --save
   creo carpeta node_modules y modifico archivo package.json (añadio dependencies):
   {
  "name": "express-server",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "marcela",
  "license": "ISC",
  "dependencies": {
    "express": "^4.16.2"
  }
}

3. npm install body-parser mongoose morgan babel-preset-es2015-node6 source-map-support --save
   añadio algunas dependencies a package.json:
   "dependencies": {
    "babel-preset-es2015-node6": "^0.4.0",
    "body-parser": "^1.18.2",
    "express": "^4.16.2",
    "mongoose": "^4.13.7",
    "morgan": "^1.9.0",
    "source-map-support": "^0.5.0"
  }
  
4. 

