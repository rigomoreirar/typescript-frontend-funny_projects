## This is for installing typescript globally
npm i typescript -g 


## For compiling a javascript based on a ts file
tsc main.ts

# defer in tag script means that the html will load the dom first before the code, like this: <script src="js/main.js" defer></script>

##  For recopiling tsc (-w means to watch)
tsc main.tsc -w
// You can also use "tsc -w", this if this is set in tsconfig.json: "rootDir": "./src"

## For initializing a tsconfig
tsc --init

## Important configuration lines in the tsconfig.json
"outDir": "./build/js" // Where js files will be created
"noEmitOnError": true // Do not compile if there are errors in the ts code
"rootDir": "./src" // Where ts files are
"target": "es2016" // Version of js

## CTRL + N to windows