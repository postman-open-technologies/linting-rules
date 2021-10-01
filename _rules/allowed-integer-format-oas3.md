---
allowed-integer-format-oas3:
  description: |-
    To improve interoperability, integer and number formats are constrained
    to a shared subset.  See recommendation RAC_REST_FORMAT_004.
  message: Type format is "{{value}}", expected one of [int32, int64]. {{path}}
  formats:
    - oas3
  severity: hint
  recommended: true
  given: |
    $.[?(@.type=="integer")]
  then:
    field: format
    function: enumeration
    functionOptions:
      values:
        - int32
        - int64 
  x-tags:
    - Formats        
...
allowed-integer-format-oas3:
  description: |-
    To improve interoperability, integer and number formats are constrained
    to a shared subset.  See recommendation RAC_REST_FORMAT_004.
  message: Type format is "{{value}}", expected one of [int32, int64]. {{path}}
  formats:
    - oas3
  severity: hint
  recommended: true
  given: |
    $.[?(@.type=="integer")]
  then:
    field: format
    function: enumeration
    functionOptions:
      values:
        - int32
        - int64 
  x-tags:
    - Formats 