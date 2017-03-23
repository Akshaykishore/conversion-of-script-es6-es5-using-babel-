This is the simple test case of converting es6 to es5 using babel.


PREREQUISITE:
-Nodejs install.
-npm install babel and related stuffs.



STEPS:
-Initally create a root folder (foreg: es6 as of my case).
-Then open the cmd and create package.json file through a command "npm init" .
-Then also install "npm install babel-cli babel-preset-es2015 --save-dev" 
this would install all the things needed for babel.
-Now if u refresh the package.json then u will get
                     "devDependencies": {
                      "babel-cli": "^6.24.0",
                      "babel-preset-es2015": "^6.24.0"
                                        }
 -Then install ".babelrc" from cmd .
 -create a src folder and include main.js in it and dist folder and include
 another main.js in it.
 -Then write the es6 code in src main.js and give "npm run build" this would 
 create a es5.js in dist main.js and thus the code is converted to es5.... 
 
 This would be the output obtained 
 ![screenshot 40](https://cloud.githubusercontent.com/assets/25049925/24239763/2e385936-0fd5-11e7-8292-22d4087d9d01.png)
![screenshot 41](https://cloud.githubusercontent.com/assets/25049925/24239764/2e38e702-0fd5-11e7-8281-ffeea9305afc.png)

