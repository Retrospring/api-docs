# API Versions

Follows non-numerical conventions, following is a list of respective version numbers.

- 1.0 - sleipnir
- 2.0 - einherjar
- ... - gungnir

## Access-Control-Allow / CORS Headers

By default the server sends these headers to any unauthorized request

```
Access-Control-Allow-Origin:   *
Access-Control-Request-Method: GET
Access-Control-Allow-Headers:  Content-Type
```

However, these will change once the request is sigend as an OAuth2 request,
which it could become one of three possible responses.

If the `Origin` header is not the same as any of the callbacks:

```
The request is denied.
```

If the `Origin` header is the same as one of the callbacks AND the OAuth token
does not have the `write` or `rewrite` scope:

```
Access-Control-Allow-Origin:   ORIGIN-OF-CALLBACK
Access-Control-Request-Method: GET
Access-Control-Allow-Headers:  Content-Type
```

If the `Origin` header is the same as one of the callbacks AND the OAuth token
does have the `write` and/or `rewrite` scopes:

```
Access-Control-Allow-Origin:   ORIGIN-OF-CALLBACK
Access-Control-Request-Method: *
Access-Control-Allow-Headers:  Content-Type
```
