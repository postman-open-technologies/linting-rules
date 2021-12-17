---
swagger-v2-schema-properties-allowed-number-format:
  description: Ensure only allowed number formats.
  message: >-
    You must have format property of decimal32, decimal64, float, double,
    decimal128
  formats:
    - oas2
  severity: hint
  recommended: true
  given: $.definitions.properties.[?(@.type=="number")]
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
swagger-v2-schema-properties-allowed-number-format:
  description: Ensure only allowed number formats.
  message: >-
    You must have format property of decimal32, decimal64, float, double,
    decimal128
  formats:
    - oas2
  severity: hint
  recommended: true
  given: $.definitions.properties.[?(@.type=="number")]
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
