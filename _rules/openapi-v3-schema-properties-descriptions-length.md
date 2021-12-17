---
openapi-v3-schema-properties-descriptions-length:
  description: Ensure that schema descriptions aren't too long.
  message: The schema description length needs to be less than 250 characters.
  severity: warn
  formats:
    - oas3
  given: $..properties.*
  then:
    field: description
    function: length
    functionOptions:
      max: 250
...
openapi-v3-schema-properties-descriptions-length:
  description: Ensure that schema descriptions aren't too long.
  message: The schema description length needs to be less than 250 characters.
  severity: warn
  formats:
    - oas3
  given: $..properties.*
  then:
    field: description
    function: length
    functionOptions:
      max: 250
