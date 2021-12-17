---
swagger-v2-schema-properties-define-array-boundaries:
  description: Requires that arrays have their minimum and maximum boundaries defined.
  message: Arrays must have minItems and maxItems defined.
  formats:
    - oas2
  severity: warn
  recommended: true
  given:
    - $.definitions.properties.[?(@.type=="array")]
  then:
    - field: maxItems
      function: defined
    - field: minItems
      function: defined
...
swagger-v2-schema-properties-define-array-boundaries:
  description: Requires that arrays have their minimum and maximum boundaries defined.
  message: Arrays must have minItems and maxItems defined.
  formats:
    - oas2
  severity: warn
  recommended: true
  given:
    - $.definitions.properties.[?(@.type=="array")]
  then:
    - field: maxItems
      function: defined
    - field: minItems
      function: defined
