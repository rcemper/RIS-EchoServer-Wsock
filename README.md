In Caché you had an example of a WebSocket Server in namespace SAMPLES  
With IRIS the samples are gone and require additional installation effort.  
   
So I refurbished the code with some useful additions:  
- independent of namespace  
- timeout control from client    
- readable communication log  
   
This contains 2 classes:  
- rcc.EchoServer.cls   
- rcc.WSScsp.cls for testing. Called from Browser by   
   (http://localhost:52773/csp/user/rcc.WSScsp.cls)

The server is essential for the 'native' WebSocket Client Demo

[Article in DC](https://community.intersystems.com/post/websocket-echo-server-iris)
