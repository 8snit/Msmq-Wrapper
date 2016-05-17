# Identity and Access Management in a Microservice Architecture

A microservice architecture consists of many independent processes. While not all of them must be externally accessible, many of them are interconnected to exchange information. This inter-process communication introduces latency and exposes the system to vulnerabilities. Effects can be mitigated by reducing security barriers and establishing trust between specific microservices, allowing to pass identity and access information throughout the system in an efficient and scalable way. This talk outlines an approach by layering OpenID Connect on top of OAuth2 using JSON Web Tokens, providing a distributed authentication mechanism where everything is standardized, self-contained and easy to replicate.

Note: this talk has not been accepted yet!

### Definitions

[OAuth2](http://oauth.net/2/) is a protocol for delegated authorization, defining how a client can receive the required tokens from a consenting user for further API access. By layering [OpenID Connect](http://openid.net/connect/) on top of OAuth2, you further gain federation capabilities, also allowing the client to retrieve further user information.

