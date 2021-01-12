# node.js

# node
 
 ## run script
  ```
   node script.js
  ```

# npm
 
 ## install package with npm
  ```
   npm install <package>
  ```

# process
 
 ## Properties and methods for current process
  ```
   process
  ```

# require function
 
 ## to require modules
  ```
   require();
  ```

# CreateServer
 
 ## Create TCP server. returns net.Server
  ```
   net.createServer([options], [connectionListener]);
  ```

# listen
 
 ## Bind on host:port. listener is executed when bound
  ```
   server.listen(port, [host], [callback]);
  ```

# close
 
 ## stop accepting new connections
  ```
   server.close();
  ```

# Express

# express server
 
 ## create express server
  ```
   const express = require('express');
  ```

# init express
 
 ## set a variable to the express
  ```
   const app = express();
  ```


# Listen
 
 ## Listen on a port
  ```
   app.listen();
  ```

# init
 
 ## creates a package.json
  ```
   npm init
  ```

# i express
 
 ## installs express
  ```
   npm i express
  ```

# port
 
 ## select port
  ```
   const PORT = process.env.PORT || 5000;
  ```

# create endpoint/route handlers
 
 ## accepting get request to the index route
  ```
   app.get('/', function(req, res) {
     res.send('<h1>Hello World</h1>')
   });
   or
   app.get('/', (req, res) => {
     res.send('<h1>Hello World</h1>')
   });
  ```
# nodemon
 
 ## restarts the server automatic
  ```
   npm i -D nodemon
  ```
# path
 
 ## node.js module to deal with file paths
  ```
   const path = require('path');
  ```
  