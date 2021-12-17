---
openapi-v3-schema-properties-define-number-boundaries:
  description: Ensures that all number properties have boundaries defined.
  message: Numeric types need to have a minimum and maximum property defined.
  formats:
    - oas3
  severity: warn
  recommended: true
  given:
    - $..properties.[?(@.type=="number")]
    - $..properties.[?(@.type=="integer")]
  then:
    - field: maximum
      function: defined
    - field: minimum
      function: defined
...
openapi-v3-schema-properties-define-number-boundaries:
  description: Ensures that all number properties have boundaries defined.
  message: Numeric types need to have a minimum and maximum property defined.
  formats:
    - oas3
  severity: warn
  recommended: true
  given:
    - $..properties.[?(@.type=="number")]
    - $..properties.[?(@.type=="integer")]
  then:
    - field: maximum
      function: defined
    - field: minimum
      function: defined
