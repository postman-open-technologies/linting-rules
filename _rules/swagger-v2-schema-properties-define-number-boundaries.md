---
swagger-v2-schema-properties-define-number-boundaries:
  description: Ensures that all number properties have boundaries defined.
  message: Numeric types need to have a minimum and maximum property defined.
  formats:
    - oas2
  severity: warn
  recommended: true
  given:
    - $.definitions.properties.[?(@.type=="number")]
    - $.definitions.properties.[?(@.type=="integer")]
  then:
    - field: maximum
      function: defined
    - field: minimum
      function: defined
...
swagger-v2-schema-properties-define-number-boundaries:
  description: Ensures that all number properties have boundaries defined.
  message: Numeric types need to have a minimum and maximum property defined.
  formats:
    - oas2
  severity: warn
  recommended: true
  given:
    - $.definitions.properties.[?(@.type=="number")]
    - $.definitions.properties.[?(@.type=="integer")]
  then:
    - field: maximum
      function: defined
    - field: minimum
      function: defined
