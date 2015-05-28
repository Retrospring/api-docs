<!-- https://github.com/rust-lang/rfcs/blob/master/0000-template.md -->
- Name: api_docs_format
- Date: 2015-05-25
- Issue: [Retrospring/api-docs#1](https://github.com/Retrospring/api-docs/issues/1)

# Summary

Outlines basic API documentation format.

# Motivation

To propose a format that uniformly marks out the layout of all API documentation.

# Detailed design

```md
# /version/path/to/namespace

Description of the API endpoint and what it entails

## formats

- Default API response formats
- `json`
- `xml`
- ...

### METHOD /version/path/to/namespace/endpoint

Description of the API

#### Parameters

if any are available

- List of parameters ordered by required first
- `name`
  - description
  - required?
  - where: `parameter location`
  - type: `parameter type`
  - default: `default value if any`

#### Additional Formats

if any additional are implemented

- `txt`
- `csv`

#### Response Codes

list of response codes

- `200 OK`
- `404 Not Found`

#### Required OAuth Scope(s)

list of required OAuth scopes (if any)

- `write`
- `moderation`

#### Rate Limit

if the endpoint is rate limited

- 15 minutes (Request interval)
- 720 requests (max requests)

#### Success Response

##### payload format in all capital letters (repeat for all)

either: a payload

```json
{"json": "payload"}
_```

or: a tag linking to a payload

```json
{"success": true, "payload": $UserPayload}
_```

#### Failure Response

##### payload format in all capital letters (repeat for all)

either: a payload

```json
{"json": "payload"}
_```

or: a tag linking to a payload

```json
{"success": false, "payload": $FailurePayload}
_```

## Payloads

### UserPayload

##### payload format in all capital letters (repeat for all)

```json
{"json": "payload"}
_```

```xml
<User>
  ...
</user>
_```
```

Strip _ from the ending code block tags

# Drawbacks

None as of yet

# Alternatives

None as of yet

# Unresolved questions
