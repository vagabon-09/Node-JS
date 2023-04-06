
   <img style="height: 100px;width: 100px;" src="https://user-images.githubusercontent.com/89797141/228059845-e5f2f614-3f9e-4a5e-b023-bd386e914798.png">

# Node-JS
Here we will be going to note down all node JS related Note what we are learning in my journey. 
For Start using node js [Download](https://nodejs.org/en/) it. Download recomended version.
# Short Notes
- `require('fs')` => use to import fs in current program
- `fs = require('fs')` => for re use fs
###  Synchronous 
``If you use Synchronous way then , first Synchronous method will execute then the other part will execute``
- `fs.mkdirSync` => crete directory
- `fs.writeFileSync` => create and write in file
- `fs.appendFileSync` => add text in next line or end of existing file
- `fs.readFileSync` => for reading file (we get buffer data to get string use `utf-8`)
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
- `localhost:yourport_number` by using this url you can see your server routing pages
- `createServer((req,res)=>{});` here `req.url` lisent the url in server
- `res.end("content")` is used to show content in webpage
- `res.writeHead(404,{"content-type":"text/html"});` is used to show status code of the page , also it shows the page type liek is it txt or html

### JSON
- `JSON.stringify()` => it is used to convert object to json
- `JSON.parse()` => use to convert json to object
- `object[i].name` => if you want to access a particular data from a simple object then you can use this eway(here i is index value)
- `object.name[i].id` => if you want ot access data form a nested object then you can use this method (here i is index value)

### Event Modules
Event module is basicaly is a Event handeling module which is use to handle events in your website
- `const EventModule = require('events')` in this way we can import events module , you must be remember first it create a class
- `const event = new EventModule() ` in this way we need to make a object and using this object we can access all function of the module
- `event.emit("checkEvent")` this is the way to create a event , also you must remember you need to add event name like `checkEvent`
- `event.on("checkEvent",()=>{// your resposend})` using this function we can handle event and in call back function we need to add responsed and you must remember ** This function should be placed before emit the event **
