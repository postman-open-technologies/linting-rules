---
openapi-v3-schema-properties-define-array-boundaries:
  description: Requires that arrays have their minimum and maximum boundaries defined.
  message: Arrays must have minItems and maxItems defined.
  formats:
    - oas3
  severity: warn
  recommended: true
  given:
    - $..properties.[?(@.type=="array")]
  then:
    - field: maxItems
      function: defined
    - field: minItems
      function: defined
...
openapi-v3-schema-properties-define-array-boundaries:
  description: Requires that arrays have their minimum and maximum boundaries defined.
  message: Arrays must have minItems and maxItems defined.
  formats:
    - oas3
  severity: warn
  recommended: true
  given:
    - $..properties.[?(@.type=="array")]
  then:
    - field: maxItems
      function: defined
    - field: minItems
      function: defined
