
# MERN-Documentation-Personal-
This is my personal MERN documentation which I use / learn from which I wrote while building my projects. Feel free to give it a star and save it for your future reference too. 



-----Let's Start with it-------
MARINATION OF THE PROJECT 😂
1. Create a new folder named "your project name"
2. Create 2 subfolders 'frontend' and 'backend'
 3.  Proceed to your /backend by doing       ```cd backend```    
4. Firstly, run `npm init -y ` to initialise ( create a package.json file)
5. Download neccessary modules = `npm install express dotenv mongoose cors`

## Creating the BackEnd:
1. in backend, create a file ( can be anything, .js) let's say server.js. \
   ```js
   const express = require("express") 
   const app = express()
   app.listen(3000, ()=> console.log("Server is running on the port 3000"))```
2. You can run it with `node server.js`. But To make it update instantly ( wrt changes in the code), \
   Proceed to *backend/package.json* and under 'scripts', you will have 'test'.  \
   Update test to :
  ```json
"dev": "node --watch server.js"
```

### Extra Info
1. Info: NPM stands for Node Package Manager.
2. `npm install` can also be written as `npm i`
3. `--watch` asks the backend or server to refresh/restart your site as soon as there is change in your code. 
