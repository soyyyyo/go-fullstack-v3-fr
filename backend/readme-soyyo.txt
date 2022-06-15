frontend: npm install
//// frontend : npm run start
backend: npm init
backend > server.js

const http = require('http');

const server = http.createServer((req, res) => {
    res.end('Voilà la réponse du serveur !');
});

server.listen(process.env.PORT || 3000);



backend : server.js (en point d'entrée)
backend : node server (rundemon server, ne fonctionne pas)

backend: sudo npm install -g nodemon
//// backend: nodemon server

backend: npm install express (framework)
backend > app.js

const express = require('express');
const app = express();
module.exports = app;

backend: npm install mongoose
creationr repo mongoose
connect application
edit du app.js


backend: npm install mongoose-unique-validator
backend: npm install bcrypt
npm install jsonwebtoken
npm install multer
