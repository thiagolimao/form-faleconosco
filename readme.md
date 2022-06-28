## Building

Install Node.js if you do not already have it installed on your machine.
Install Gulp CLI. Run the below command in your terminal. This will install Gulp CLI globally.

```
	# Setup
	npm install gulp-cli -g
```

In the project folder install dependences:

```
	npm install
```

In the project folder run:

```
	npm start
```

Access the project through `http://localhost:3000/`

Compiles and exports the project to the /dist folder:

```
	npm run dist
```

It will watch and automatically compile the project to the /dist folder each time you edit and save a file inside the /src folder

```
	npm run watch
```
