---
openapi-v3-schema-properties-names-length:
  description: Ensuring that property names are no more than 25 characters.
  message: Schema property names should be less than 25 characters .
  severity: error
  given: $..properties.*
  then:
    field: '@key'
    function: length
    functionOptions:
      max: 25
...
openapi-v3-schema-properties-names-length:
  description: Ensuring that property names are no more than 25 characters.
  message: Schema property names should be less than 25 characters .
  severity: error
  given: $..properties.*
  then:
    field: '@key'
    function: length
    functionOptions:
      max: 25
