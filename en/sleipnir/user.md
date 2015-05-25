# /sleipnir/user

APIs that interact with users.

## Formats

- json

### /sleipnir/user/:id/avatar

Retrieve an URL leading to an avatar

#### Parameters

- id
  - ID of the user
  - required
  - path
  - number
- redirect
  - Redirect to the resulting URL
  - optional
  - query
  - boolean
  - false

#### Additional Formats

- txt

#### Response Codes

- 200 OK
- 404 Not Found

#### Success Response

##### JSON

```json
{"avatar": "http://an.url.to/image.png"}
```

##### TXT
```plain
http://an.url.to/image.png
```

#### Failure Response

##### JSON

```json
{"avatar": ""}
```

##### TXT

```
NULL
```

### /sleipnir/user/:id/header

Retrieve an URL leading to a header image

#### Parameters

- id
  - ID of the user
  - required
  - path
  - number
- redirect
  - Redirect to the resulting URL
  - optional
  - query
  - boolean
  - false

#### Additional Formats

- txt

#### Response Codes

- 200 OK
- 404 Not Found

#### Success Response

##### JSON

```json
{"header": "http://an.url.to/image.png"}
```

##### TXT
```plain
http://an.url.to/image.png
```

#### Failure Response

##### JSON

```json
{"header": ""}
```

##### TXT

```
NULL
```

## Payloads
