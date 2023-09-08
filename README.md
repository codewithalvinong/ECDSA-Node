# ECDSA-Node
This project is an example of using a client and a server to facilitate transfers between different addresses. Since there is only one server in the back end handling the transfer, this is clearly  centralized. We will not be interested in distributed consensus for this project.

 However,  we want to integrate public key cryptography. By using elliptic curve digital signatures, we can ensure that the server only allows money transfers  signed  by the owner of the relevant address. 

### Client

The client folder contains a [react app](https://reactjs.org/) using [vite](https://vitejs.dev/). To get started, follow these steps:

1. Open up a terminal in the `/client` folder
2. Run `npm install` to install all the depedencies
3. Run `npm run dev` to start the application

### Server

The server folder contains a node.js server using [express](https://expressjs.com/). To run the server, follow these steps:

1. Open a terminal within the `/server` folder
2. Run `npm install` to install all the depedencies
3. Run `node index` to start the server

The application should connect to the default server port (3042) automatically!

