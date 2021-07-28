# Introduction to JSON Web Tokens

> _JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object._

> **JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.**

## When should you use JSON Web Tokens?

> **Authorization:** _Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token._

**Single Sign On** _is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains._

> **Information Exchange:** _JSON Web Tokens are a good way of securely transmitting information between parties._

_Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are._

_As the signature is calculated using the header and the payload, you can also verify that the content hasn't been tampered with._

## What is the JSON Web Token structure?

> _In its compact form, JSON Web Tokens consist of three parts separated by dots `.`, which are:_

1. **Header**
2. **Payload**
3. **Signature**

## Header

> _The header typically consists of two parts: the type of the token, which is JWT, and the signing algorithm being used, such as HMAC SHA256 or RSA._

- **Public claims**: _These can be defined at will by those using JWTs. But to avoid collisions they should be defined in the IANA JSON Web Token Registry or be defined as a URI that contains a collision resistant namespace._

- **Private claims**: _These are the custom claims created to share information between parties that agree on using them and are neither registered or public claims._
