Crossplatform network Protohx example. :)

[Compiled demos (node.js/neko server and html5/android/flash/linux/node.js clients) ](https://bitbucket.org/nitrobin/protohx/downloads/protohx-demo.tar.gz)


## Client targets
### Client implemented for most of NME targets:
* html5 (via socket.io) [live demo here](http://protohx.ap01.aws.af.cm/)
* linux, android (sys.net.Socket)
* flash  (flash.net.Socket)


## Server targets
###neko
* server.native.MainServer - simple neko socket server based on neko.net.ThreadServer.

###node.js
* server.nodejs.BotClient - node.js TCP-socket bot client;
* server.nodejs.NetServer - node.js server with TCP-socket clients support (flash, cpp);
* server.nodejs.SocketIoServer - node.js server with socket.io clients support (html5);
* server.nodejs.MultiServer - node.js server with TCP-socket and socket.io clients support (html5, flash, cpp).

Server logic implemented in server.logic.SessionRegistry
