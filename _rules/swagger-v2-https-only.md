---
swagger-v2-https-only:
  description: Ensures that all APIs are only using HTTPS protocol as a transport.
  message: You must only use HTTPS for the schemes.
  severity: error
  formats:
    - oas2
  type: style
  given: $.schemes
  then:
    function: schema
    functionOptions: null
    schema:
      type: string
      items: null
      enum:
        - https
      maxItems: 1
...
swagger-v2-https-only:
  description: Ensures that all APIs are only using HTTPS protocol as a transport.
  message: You must only use HTTPS for the schemes.
  severity: error
  formats:
    - oas2
  type: style
  given: $.schemes
  then:
    function: schema
    functionOptions: null
    schema:
      type: string
      items: null
      enum:
        - https
      maxItems: 1
