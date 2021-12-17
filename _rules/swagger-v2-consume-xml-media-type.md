---
swagger-v2-consume-xml-media-type:
  description: Ensures that application/xml media types are able to be consumed.
  message: The APIs should be able to consume application/xml media types.
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
          - application/xml
...
swagger-v2-consume-xml-media-type:
  description: Ensures that application/xml media types are able to be consumed.
  message: The APIs should be able to consume application/xml media types.
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
          - application/xml
