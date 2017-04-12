API Proxy can be built from several components. This document describes common API proxy components.

# Outline

## authentication (identity provider)
- key based
- oauth2
- JSON Web Tokens
  
## authorization
- rule /role based
  
## Caching

## Load balancing

## Logging
Logging consists of recording header information for reqests and responses made through the gateway/proxy. Care should be taken not to log private information, such as request/response body.

## rate limiting
There are several common ways to measure requests for rate limiting:
- api key based
- IP address based
- custom header key/value based

## Transformation
- request rewriting
- response rewriting
