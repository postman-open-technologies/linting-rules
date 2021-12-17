---
swagger-v2-schema-description-length:
  description: All schemas descriptions should be shorter than 20 characters.
  message: Description needs to be less than 20 characters.
  severity: warn
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: description
    function: length
    functionOptions:
      max: 20
...
swagger-v2-schema-description-length:
  description: All schemas descriptions should be shorter than 20 characters.
  message: Description needs to be less than 20 characters.
  severity: warn
  formats:
    - oas2
  given: $.definitions.*
  then:
    field: description
    function: length
    functionOptions:
      max: 20
