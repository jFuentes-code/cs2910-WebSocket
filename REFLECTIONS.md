A description of what security vulnerabilities may be in you application?

This application is vulnerable to xss injections because it takes input from clients without cleaning the data and spits it out to all other clients. 
This leaves opputunity for a client side attack where malicious scripts may be uploaded and ran by all other clients. However, taking in input from a
user and outputting it to all clients is by design what the application is meant to do so, assuming there is no data handling happening on the websocket
OWASP's Insecure Design may be an additional vulnerablity in the application.

What did you learn from this exercise?

I learned a lot from this process, but I most enjoyed learning about websockets and the different events that can be used to handle outgoing and incoming
data over the websocket. This constant stream of data is a newly defined concept to me, and while it makes sense to have an api to handle this type of data
transfering, it now makes sense how real time information can be transmitted without constant GET and PUT headers.
