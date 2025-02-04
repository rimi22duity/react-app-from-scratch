This is a React App that was built from the scratch to understand the react background workflow.

```npm run build``` - this command will only generate a dist folder containing bundle.js (as per ```webpack.config.js```) 

You can use live-server extention to test if it is giving any errors or not.

## Concepts:
1. Webpack is needed to rewrite JSX to plain Javascript
2. ```npm init -y``` creates the package.json
3. ```@babel/preset-env``` will take care of the import and export syntax
4. ```@babel/preset-react``` will take care of the jsx syntax
5. You can mention in ```webpack.config.js``` where to store the ```bundle.js``` file.
