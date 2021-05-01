# Authorizing requests and identifying your application

Every request your application sends to the Books API needs to identify your application to Google

# two ways to identify your application:

1. using an OAuth 2.0 token
1. using the application's API key.

- Authorizing requests with OAuth 2.0

* OAuth 2.0: Whenever your application requests private user data, it must send an OAuth 2.0 token along with the request. Your application first sends a client ID and, possibly, a client secret to obtain a token. You can generate OAuth 2.0 credentials for web applications, service accounts, or installed applications.

* API keys: A request that does not provide an OAuth 2.0 token must send an API key. The key identifies your project and provides API access, quota, and reports.

# What is EJS?

EJS is a simple templating language that lets you generate HTML markup with plain JavaScript

# Features

1. Fast compilation and rendering
1. Simple template tags: <% %>
1. Custom delimiters (e.g., use [? ?] instead of <% %>)
1. Sub-template includes
1. Ships with CLI
1. Both server JS and browser support
1. Static caching of intermediate JavaScript
1. Static caching of templates
1. Complies with the Express view system
