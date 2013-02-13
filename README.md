# PeerJS Server: Server component for PeerJS #

PeerServer helps broker connections between PeerJS clients. Data is not proxied through the server.

##[http://peerjs.com](http://peerjs.com)


**If you prefer to use a cloud hosted PeerServer instead of running your own, [sign up for a free API key here](http://peerjs.com/peerserver)**


### Run PeerServer

Install the library

    npm install peer     

Run the server

    var PeerServer = require('peer-cloud').PeerServer;
    var server = new PeerServer({ port: 9000 });
    
Connecting to the server from PeerJS
    
    // No API key requried when not using cloud server
    var peer = new Peer('someid', {host: 'localhost', port: 9000});
    
