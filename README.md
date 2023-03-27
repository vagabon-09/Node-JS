![node-js](https://user-images.githubusercontent.com/89797141/228059845-e5f2f614-3f9e-4a5e-b023-bd386e914798.png)

# Node-JS
Here we will be going to note down all node JS related Note what we are learning in my journey. 
For Start using node js [Download](https://nodejs.org/en/) it. Download recomended version.
# Short Notes
- `require('fs')` => use to import fs in current program
- `fs = require('fs')` => for re use fs
###  Synchronous Way
- `fs.mkdirSync` => crete directory
- `fs.writeFileSync` => create and write in file
- `fs.appendFielSync` => add text in next line or end of existing file
- `fs.readFielSync` => for reading file (we get buffer data to get string use `utf-8`)
- `fs.renameSync` => for renaming file 
- `fs.rmdirSync` => for removing directory
- `fs.unlinkSync` => for removing or delete file

###  Asynchronous Way
- `fs.mkdir` => crete directory
- `fs.writeFile` => create and write in file
- `fs.appendFiel` => add text in next line or end of existing file
- `fs.readFiel` => for reading file (we get buffer data to get string use `utf-8`)
- `fs.rename` => for renaming file 
- `fs.rmdir` => for removing directory
- `fs.unlink` => for removing or delete file

### Path Modules
- `path.dirname()` => for getting file location
- `path.extname()` => for getting file extention type
- `path.basename()` => for getting file name
- `path.parse()` => for getting all data about file in a object
- `parthParseObject`.`objectType` => for getting data form object.


  For more information click [here](https://nodejs.org/dist/latest-v18.x/docs/api/path.html)
  
 ### Import Export Module
 - `module.exports={name of the functions}` => You can export modules. You can export multiple funciton by separating `,` and here `exports` will be a object
 - `const variable = require("path of the module")` => By requiring you can use modules in desire file
 - `const {name of the modules} = require("path of the modules)` => Using this method you can access all the modules just by their name

## Node module
Some importent notemodules 
 - [chalk](https://www.npmjs.com/package/chalk)
 - [NodeMon](https://www.npmjs.com/package/nodemon)
 - [Validator](https://www.npmjs.com/package/validator)

if you like to explore more module click [here](https://www.npmjs.com/)

### Node Package Manager
- `npm init` => to install npm use this command
- `npm install module_name` or `npm i module_name` => use to install new module 
- `npm install module_name@version` => use to install with version

### Http Server
- First require `http` module (`http`)
- `createServer((req,res)=>{// Manage request})` use to create server
- `req.end()` use to manage request
- `server.listen(port,"localhost",()=>{responserd})` user to listen server response , here in place of port you sould place a port number and in place of localhost        place you need to place ip number normaly it is 127.0.0.1
