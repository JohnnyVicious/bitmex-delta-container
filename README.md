# bitmex-delta-container
Container of bitmex-delta-server

Based on NodeJS Alpine image. 

Container will generate a config at start-up.
You can set environment variables on your container for custom settings, they get polled every start.

HTTP interface running internal on TCP 4444, default this will get exposed on your container on a random port.

http://'<your-container-IP>':'<attached-port>'

Solution for Bitmex Official Delta Server
https://github.com/BitMEX/api-connectors/tree/master/official-ws/delta-server
