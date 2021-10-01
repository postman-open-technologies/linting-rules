---
request-bodies-xml:
  description: Payload must be in xml format
  message: Payload must be in xml format, please correct the format for {{path}}.
  recommended: true
  type: style
  given: $.paths.*.*.requestBody.*
  severity: warn
  resolved: false
  then:
  - field: application/xml
    function: truthy
...
request-bodies-xml:
  description: Payload must be in xml format
  message: Payload must be in xml format, please correct the format for {{path}}.
  recommended: true
  type: style
  given: $.paths.*.*.requestBody.*
  severity: warn
  resolved: false
  then:
  - field: application/xml
    function: truthy