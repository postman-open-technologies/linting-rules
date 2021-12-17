---
swagger-v2-produce-json-media-type:
  description: Ensures that application/json media types are able to be produced.
  message: The APIs should be able to produce application/json media types.
  severity: error
  recommended: true
  format: oas2
  given: $..produces.*
  then:
    function: schema
    functionOptions:
      schema:
        type: string
        enum:
          - application/json
...
swagger-v2-produce-json-media-type:
  description: Ensures that application/json media types are able to be produced.
  message: The APIs should be able to produce application/json media types.
  severity: error
  recommended: true
  format: oas2
  given: $..produces.*
  then:
    function: schema
    functionOptions:
      schema:
        type: string
        enum:
          - application/json
