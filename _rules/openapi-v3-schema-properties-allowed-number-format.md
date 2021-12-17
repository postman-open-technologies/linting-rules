---
openapi-v3-schema-properties-allowed-number-format:
  description: Ensure only allowed number formats.
  message: >-
    You must have format property of decimal32, decimal64, float, double,
    decimal128
  formats:
    - oas3
  severity: hint
  recommended: true
  given: $..properties.[?(@.type=="number")]
  then:
    field: format
    function: enumeration
    functionOptions:
      values:
        - decimal32
        - decimal64
        - float
        - double
        - decimal128
...
openapi-v3-schema-properties-allowed-number-format:
  description: Ensure only allowed number formats.
  message: >-
    You must have format property of decimal32, decimal64, float, double,
    decimal128
  formats:
    - oas3
  severity: hint
  recommended: true
  given: $..properties.[?(@.type=="number")]
  then:
    field: format
    function: enumeration
    functionOptions:
      values:
        - decimal32
        - decimal64
        - float
        - double
        - decimal128
