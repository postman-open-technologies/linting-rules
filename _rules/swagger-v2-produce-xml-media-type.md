---
swagger-v2-produce-xml-media-type:
  description: Ensures that application/xml media types are able to be produced.
  message: The APIs should be able to produce application/xml media types.
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
          - application/xml
...
swagger-v2-produce-xml-media-type:
  description: Ensures that application/xml media types are able to be produced.
  message: The APIs should be able to produce application/xml media types.
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
          - application/xml
