frontend: npm install
frontend : npm run start
backend: npm init
backend > server.js

const http = require('http');

const server = http.createServer((req, res) => {
    res.end('Voilà la réponse du serveur !');
});

server.listen(process.env.PORT || 3000);



backend : server.js (en point d'entrée)
backend : node server (rundemon server, ne fonctionne pas)