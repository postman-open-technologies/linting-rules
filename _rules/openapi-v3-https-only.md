---
openapi-v3-https-only:
  description: Ensures that all APIs are only using HTTPS protocol as a transport.
  message: You must only use HTTPS for the server transport protocol.
  formats:
    - oas3
  severity: error
  given: $.servers..url
  then:
    function: pattern
    functionOptions: null
    match: /^https:/
...
openapi-v3-https-only:
  description: Ensures that all APIs are only using HTTPS protocol as a transport.
  message: You must only use HTTPS for the server transport protocol.
  formats:
    - oas3
  severity: error
  given: $.servers..url
  then:
    function: pattern
    functionOptions: null
    match: /^https:/
