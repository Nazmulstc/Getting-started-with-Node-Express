## Getting-Started-with-Node-Express
1. mkdir myapp = to Creact Folder.
2. cd myapp = To go diractory File.
3. code . = to open vs Code.
4. npm init/npm init -y = to initialize node pakege management syestem.
5. npm install express --save/npm i express = Install express in my projects.
6. Create index.js File.

## Then Five Task:

$ const express = require("express") = To Import Express File.

$ const app = express() = To set Express.

$ const port = process.env.PORT || 3000 = Where Open Your File.

$ app.get('/', (req, res) => {
  res.send('Hello World!')
})

$ app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`)
})

## Optional
$ node index.js
$ npm install -g nodemon = to Monitor node file Or Auto Relode web Page.
$ nodemon index.js
