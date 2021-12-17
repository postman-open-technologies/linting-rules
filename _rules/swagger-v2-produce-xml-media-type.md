---
swagger-v2-produce-xml-media-type:
  description: Ensures that an API produces application/xml media type.
  message: APIs should produce a application/xml media type.
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
swagger-v2-produce-xml-media-type:
  description: Ensures that an API produces application/xml media type.
  message: APIs should produce a application/xml media type.
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
