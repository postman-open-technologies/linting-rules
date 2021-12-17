---
swagger-v2-produce-json-media-type:
  description: Ensures that an API produces application/json media type.
  message: APIs should produce a application/json media type.
  severity: error
  recommended: true
  format: oas2
  given: $..consumes.*
  then:
    function: schema
    functionOptions:
      schema:
        type: string
        enum:
          - application/json
...
swagger-v2-produce-json-media-type:
  description: Ensures that an API produces application/json media type.
  message: APIs should produce a application/json media type.
  severity: error
  recommended: true
  format: oas2
  given: $..consumes.*
  then:
    function: schema
    functionOptions:
      schema:
        type: string
        enum:
          - application/json
