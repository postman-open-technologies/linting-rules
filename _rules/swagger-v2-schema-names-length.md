---
swagger-v2-schema-names-length:
  description: Ensure schema names should be no more than 25 characters.
  message: All schema names should be less than 25 characters.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: length
    functionOptions:
      max: 25
...
swagger-v2-schema-names-length:
  description: Ensure schema names should be no more than 25 characters.
  message: All schema names should be less than 25 characters.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: length
    functionOptions:
      max: 25
