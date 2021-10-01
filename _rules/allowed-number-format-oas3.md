---
allowed-number-format-oas3:
  description: |-
    To improve interoperability, integer and number formats are constrained
    to a shared subset. See recommendation RAC_REST_FORMAT_004.
  message: Type format is "{{value}}", expected one of [decimal32, decimal64,
    decimal128, float, double]. {{path}}
  formats:
    - oas3
  severity: hint
  recommended: true
  given: |
    $.[?(@.type=="number")]
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
  x-tags:
    - Formats        
...
allowed-number-format-oas3:
  description: |-
    To improve interoperability, integer and number formats are constrained
    to a shared subset. See recommendation RAC_REST_FORMAT_004.
  message: Type format is "{{value}}", expected one of [decimal32, decimal64,
    decimal128, float, double]. {{path}}
  formats:
    - oas3
  severity: hint
  recommended: true
  given: |
    $.[?(@.type=="number")]
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
  x-tags:
    - Formats   