# /sleipnir

Sleipnir API (1.0)

# Parameters

These are global, apply to each endpoint but they might not do anything.

- `nanotime`
  - Multiply timestamps by 1000, for languages such as JavaScript
  - optional
  - where: `query`
  - type: `boolean`
  - default: `false`
  - CAVEAT: Regardless of value, it will always be `TRUE` however if will be `FALSE` without a value
- `id_to_string`
  - Cast IDs to Strings, particularly useful when they're larger than the safe max integer.
  - optional
  - where: `query`
  - type: `boolean`
  - default: `false`
  - CAVEAT: Regardless of value, it will always be `TRUE` however if will be `FALSE` without a value
