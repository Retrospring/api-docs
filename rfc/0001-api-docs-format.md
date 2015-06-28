<!-- https://github.com/rust-lang/rfcs/blob/master/0000-template.md -->
- Name: api_docs_format
- Date: 2015-05-25
- Issue: [Retrospring/api-docs#1](https://github.com/Retrospring/api-docs/issues/1)

## Summary

Outlines basic API documentation format.

## Motivation

To propose a format that uniformly marks out the layout of all API documentation.

## Detailed design

### Namespace

stored in /lang/version/namespace.md

```md
# /version/path/to/namespace/

Description of the API namespace

## formats

- Default API response formats
- `json`
- `xml`
- ...

## endpoints

### [METHOD endpoint](namespace/endpoint.md)

`METHOD https://retrospring.net/version/path/to/namespace/endpoint.json`

Short description of the API endpoint

##### last revision date
```

### endpoint

stored in /lang/version/namespace/endpoint.md

```md
# METHOD /version/path/to/namespace/endpoint

Description of the API endpoint and what it entails

## additional formats

- Endpoint specific formats

## request parameters

- List of request parameters

## caveats

- throttling, oauth, etc

## responses

- list of responses, each headered

## error codes

- list of error codes

##### last revision date
```

### payload

stored in /lang/version/payload/name.md

```md
# PayloadName

Description of the payload

## example

code block of example response

##### last revision date
```

Strip _ from the ending code block tags

# Drawbacks

None as of yet

# Alternatives

None as of yet

# Unresolved questions
