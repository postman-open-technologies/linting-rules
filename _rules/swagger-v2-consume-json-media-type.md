---
swagger-v2-consume-json-media-type:
  description: Ensures that application/json media types are able to be consumed.
  message: The APIs should be able to consume application/json media types.
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
swagger-v2-consume-json-media-type:
  description: Ensures that application/json media types are able to be consumed.
  message: The APIs should be able to consume application/json media types.
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
