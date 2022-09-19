# githubtest
hello
const { createServer } = require('http');

const server = createServer((request,response) => { 
    response.writeHead(200,{ 'content-Type':'text/html'});
    response.write('<h3><title>Hello World!</title><br><p> Personal Informations<br> </p><p>Name : Nway Thandar Zaw <br><p> Age : 21 </p> <p>Address: Yangon</p></h3>');
})

server.listen(8080);
