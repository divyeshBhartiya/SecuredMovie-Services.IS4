# SecuredMovie-Services.IS4
Securing microservices with using standalone Identity Server 4 and backing with Ocelot API Gateway. 

We’re going to protect our ASP.NET Web MVC and API applications with using OAuth 2 and OpenID Connect in IdentityServer4. Securing your web application and API with tokens, working with claims, authentication and authorization middlewares and applying policies, and so on.

We will have 3 asp.net core microservices project which we are going to develop one by one.

## Movies.API

First of all, we are going to develop Movies.API project and protect this API resources with IdentityServer4 OAuth 2.0 implementation. Generate JWT Token with client_credentials from IdentityServer4 and will use this token for securing Movies.API protected resources.

## Movies.MVC

After that, we are going to develop Movies.MVC Asp.Net project for Interactive Client of our application. This Interactive Movies.MVC Client application will be secured with OpenID Connect in IdentityServer4. Our client application pass credentials with logging to an Identity Server and receive back a JSON Web Token (JWT).

## Identity Server

Also, we are going to develop centralized standalone Authentication Server and Identity Provider with implementing IdentityServer4 package and the name of microservice is Identity Server.
Identity Server4 is an open source framework which implements OpenId Connect and OAuth2 protocols for .Net Core.
With Identity Server, we can provide authentication and access control for our web applications or Web APIs from a single point between applications or on a user basis.

## Areas Covered:

Building IdentityServer4 Authentication Microservice

Get Token from Identity Server with client_credentials grant_type

Protecting API with Using IdentityServer4 OAuth 2.0 and JWT Token

OpenID Connect with IdentityServer4 For Interactive MVC Client Micorservice

IdentityServer4 OpenID Connect Integration For Client MVC Interactive Client Application

Consume Protected API with HttpClientFactory From Client Application

Adding the UI for OpenID Connect Login, logout, consent and error

Hybrid Flow of IdentityServer4 Secure Interactive Mvc Client (OpenID) and Api Resources (OAuth2)

Claim Based Authorization in IdentityServer4 Secure Interactive MVC Client (OpenID) and API Resources (OAuth2)

Claim Based Authentication with client_id Claim Restriction

Securing API with JWT Bearer Token Authentication

Build OpenId Connect Interactive Client for Client MVC Application

Developing HttpHandler for Getting Token from IDPClient with IHttpClientFactory
