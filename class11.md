[GitHub](https://batoolalali.github.io/401-Reading-notes/class11)

## User Modeling

Some information, like emails, user names, and addresses can be stored in plain text, as long as the database is password protected and/or behind a firewall. Other information, like a users password, should be encrypted using a hashing algorithm before it is ever stored. User models that have sensitive data that should NEVER be sent to client applications. 

## Cryptography
Cryptography is the science which studies methods for encoding messages so that they can be read only by a person who knows the secret information required for decoding


## Hash Algorithms
If identical data is passed into the algorithm the same hash will always be produced. Hash algorithms are often used for checking the integrity of data.

A hash password can be stored when the user signs up. When the user needs to login, they can resend their password and the server can hash the login password using the same hash algorithm. The server can then compare the hashed login password with previously stored hashed password to determine if the user should be authenticated.

## Cypher Algorithms
User tokens can be created by associated a random unique string (tokenSeed) with a user account and, in turn, encrypting the tokenSeed with a secret key that only the server knows. We can then send the encrypted token to a client application. When the client makes a future request they send back the token. The server can reverse the token into the tokenSeed by decrypting it with the secret key, the tokenSeed was unique to the database and can be queried to produce the user who made the request.

## Basic Authorization
Basic Authorization is a common method used to send a username and password in an HTTP request. 
