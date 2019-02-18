This will run a simple "Hello World!".

The Dockerfile does not expose any ports. The webserver will by default listen on port `4001`. You must expose when using docker run or docker compose the port 4001 or set a new port and expose.

You can customize the port by adding an enviorment variable WEB_SERVER_PORT with the port number `WEB_SERVER_PORT=4002` would overide the default value and listen on port 4002. 
