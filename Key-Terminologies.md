## Password Anti-pattern

The Password Anti-Pattern, in which a shared secret (the password) directly represents the party in question (the user). By sharing this secret password with applications, the user enables applications to access protected APIs.

![Password anti-pattern](assets/password-anti-pattern.png)

## OAuth 2.0

![OAuth flwo](assets/oauth-2.png)

OAuth 2 is a standard for delegating authorization for accessing resources via HTTP.

OAuth 2 is specified and standardized by the IETF in RFC6749.

[http://tools.ietf.org/html/rfc6749](http://tools.ietf.org/html/rfc6749)

## OAuth Actors

- OAuth provider has the following 3 components
    - Authentication Component
    - Concent Server
    - Token management infrastructure
- Resource provider (hosts user's data)
- Resource owner (User)
- Client (Application)
    - Wants to access resources
    - Gets and holds Access Token and Refresh Token
    - Should not hold password of Resource Owner
    - Identified via ClientID and ClientSecret

![client](assets/client.png)
![client](assets/auth-server-components.png)
![client](assets/auth-server-endpoints.png)
![client](assets/resource-server.png)

## OAuth Endpoints

    - Authorization Endpoint
    - Token Endpoint
    - Redirect Endpoint
    - Resource Endpoint

![OAuth Server : Authorization Endpoint](assets/oauth-server-authorization-endpoint.png)

![OAuth Server : Token Endpoint](assets/oauth-server-token-endpoint.png)

![Client : Redirect Endpoint](assets/client-redirect-endpoint.png)

![Resource Server : Resource Endpoint](assets/resource-server-resource-endpoint.png)