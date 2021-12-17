---
swagger-v2-schema-properties-allowed-integer-format:
  description: Requires integer properties to have a format of int32 or int64.
  message: Type format should be be int32 or int64.
  formats:
    - oas2
  severity: hint
  recommended: true
  given: $.definitions.properties.[?(@.type=="integer")]
  then:
    field: format
    function: enumeration
    functionOptions:
      values:
        - int32
        - int64
...
swagger-v2-schema-properties-allowed-integer-format:
  description: Requires integer properties to have a format of int32 or int64.
  message: Type format should be be int32 or int64.
  formats:
    - oas2
  severity: hint
  recommended: true
  given: $.definitions.properties.[?(@.type=="integer")]
  then:
    field: format
    function: enumeration
    functionOptions:
      values:
        - int32
        - int64
