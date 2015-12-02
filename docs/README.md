# Documentation

This wiki will guide you through all the things you need to successfully integrate an OAuth 2.0 compliant server into your Laravel applications. Let's begin!

## Getting Started
1. [Introduction](getting-started/introduction.md)
2. [Terminology](getting-started/terminology.md)
3. [Laravel 4 Installation](getting-started/laravel-4.md)
4. [Laravel 5 Installation](getting-started/laravel-5.md)
5. [Lumen Installation](getting-started/lumen.md)
6. [Configuration](getting-started/config)
7. [Apache ModRewrite](getting-started/apache.md)

## Authorization Server
1. [Choosing a Grant](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Choosing-a-Grant)
2. Implementing an Authorization Server
    1. [With the Client Credentials Grant](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Implementing-an-Authorization-Server-With-the-Client-Credentials-Grant)
    2. [With the Password Grant](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Implementing-an-Authorization-Server-with-the-Password-Grant)
    3. [With the Auth Code Grant](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Implementing-an-Authorization-Server-with-the-Auth-Code-Grant)
    4. [With the Refresh Token Grant](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Implementing-an-Authorization-Server-with-the-Refresh-Token-Grant)
3. Extending the server
    1. Using a different storage
    2. [Creating your own grant type](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Creating-your-own-custom-Grant)

## Resource Server
1. [Securing your API endpoints](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Securing-your-API-endpoints)
    2. [Defining scopes](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Securing-your-API-endpoints#defining-scopes)
    3. [Checking the access token](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Securing-your-API-endpoints#checking-the-access-token)
    4. [Checking the scopes](https://github.com/lucadegasperi/oauth2-server-laravel/wiki/Securing-your-API-endpoints#checking-the-scopes)
