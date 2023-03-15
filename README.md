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
