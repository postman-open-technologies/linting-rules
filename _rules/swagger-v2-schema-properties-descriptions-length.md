---
swagger-v2-schema-properties-descriptions-length:
  description: Ensure that schema descriptions aren't too long.
  message: The schema description length needs to be less than 250 characters.
  severity: warn
  formats:
    - oas2
  given: $.definitions.properties.*
  then:
    field: description
    function: length
    functionOptions:
      max: 250
...
swagger-v2-schema-properties-descriptions-length:
  description: Ensure that schema descriptions aren't too long.
  message: The schema description length needs to be less than 250 characters.
  severity: warn
  formats:
    - oas2
  given: $.definitions.properties.*
  then:
    field: description
    function: length
    functionOptions:
      max: 250
