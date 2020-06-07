[GitHub](https://batoolalali.github.io/401-Reading-notes/class12)

## OAUTH2.0
OAuth is “an open standard for access delegation”, serves as a way to give users the ability to grant application access to services, without giving the application their password.

## What are some of the benefits as a client/user to using OAuth?
It allows limited access to the user's data and allows accessing when authorization tokens expire. It has ability to share data for users without having to release personal information. It is easier to implement and provides stronger authentication.

## How does OAuth work?
Through a series of “handshakes”, an application such as an Express Web Server asks the user if it’s ok to login as them at some remote service, and then begins the process of authentication and access.

## Access Code
First the client needs to grant the application permission. To do this you need to provide an `<a>` tag that will take them to the service’s authorization page. This `<a>` tag should pass the following information through a query string to the authorization server. Every service is slightly different in their specific requirements, but in some form or another, variables like these are part of this initial request

- `response_type=code`
- `client_id=<your client id>`
- `redirect_uri=<your redirect uri>`
- `scope=<list of scopes>` 
- `state=<anything you want>` 
