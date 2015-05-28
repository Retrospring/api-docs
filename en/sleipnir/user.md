# /sleipnir/user

APIs that interact with users.

## Formats

- `json`
- `msgpack`

### GET /sleipnir/user/:id/avatar

Retrieve an URL leading to an avatar

#### Parameters

- `id`
  - ID of the user
  - required
  - where: `path`
  - type: `number`
- `redirect`
  - Redirect to the resulting URL
  - optional
  - where: `query`
  - type: `boolean`
  - default: `false`
- `size`
  - Size to render or redirect to (TXT, Redirect only!)
  - optional
  - where: `query`
  - type: `string`
  - default: `medium`

#### Additional Formats

- `txt`

#### Response Codes

- `200 OK`
- `404 Not Found`

#### Success Response

##### JSON

```json
{
  "avatar":{
    "large":"http://localhost:3000/system/users/profile_pictures/xxx/yyy/zzz/large/avatar.jpg",
    "medium":"http://localhost:3000/system/users/profile_pictures/xxx/yyy/zzz/medium/avatar.jpg",
    "small":"http://localhost:3000/system/users/profile_pictures/xxx/yyy/zzz/small/avatar.jpg"
  }
}
```

##### TXT
```plain
http://localhost:3000/system/users/profile_pictures/xxx/yyy/zzz/large/medium.jpg
```

#### Failure Response

##### JSON

```json
{
  "message": "Couldn't find User with 'id'=x",
  "status":404
}
```

##### TXT

```
NULL
```

### GET /sleipnir/user/:id/header

Retrieve an URL leading to a header image

#### Parameters

- `id`
  - ID of the user
  - required
  - where: `path`
  - type: `number`
- `redirect`
  - Redirect to the resulting URL
  - optional
  - where: `query`
  - type: `boolean`
  - default: `false`
- `size`
  - Size to render or redirect to (TXT, Redirect only!)
  - optional
  - where: `query`
  - type: `string`
  - default: `web`


#### Additional Formats

- `txt`

#### Response Codes

- `200 OK`
- `404 Not Found`

#### Success Response

##### JSON

```json
{
  "header":{
    "web":"http://localhost:3000/system/users/profile_headers/xxx/yyy/zzz/web/header.jpg",
    "mobile":"http://localhost:3000/system/users/profile_headers/xxx/yyy/zzz/mobile/header.jpg",
    "retina":"http://localhost:3000/system/users/profile_headers/xxx/yyy/zzz/retina/header.jpg"
  }
}
```

##### TXT
```plain
http://localhost:3000/system/users/profile_headers/xxx/yyy/zzz/web/header.jpg
```

#### Failure Response

##### JSON

```json
{
  "message": "Couldn't find User with 'id'=x",
  "status":404
}
```

##### TXT

```
NULL
```

## Payloads
