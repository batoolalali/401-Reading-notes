[GitHub](https://batoolalali.github.io/401-Reading-notes/class13)

## Bearer Authentication
Following a signin attempt, your service is able to make a boolean decision as to the success of the attempt.
Rather than continually sending username+password over the internet, or undergoing the long OAuth process, we are able to use a secondary authentication method called “Bearer Token”

Bearer Tokens are encoded JSON objects that “bear” or “contain” enough information for the server to assert that any client request that presents a valid token must have originated from a client.

In express servers, this can be done in middleware, in conjunction with a user model

## JSON Web Token (JWT) 
is an open standard that defines a compact and self-contained way for securely transmitting information between parties (servers, clients, etc) as a JSON object.

public/private key pair using RSA or ECDSA.

## When should you use JSON Web Tokens?
Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains.

JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header and the payload.