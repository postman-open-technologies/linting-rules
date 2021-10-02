---
response-error-standardized:
  description: Error response body should conform to Microsoft Azure API Guidelines.
  message: '{{error}}'
  severity: warn
  formats:
  - oas2
  given: $.paths[*][*].responses
  then:
    function: error-response
  x-status: draft
  x-tags:
      - Tag       
...
response-error-standardized:
  description: Error response body should conform to Microsoft Azure API Guidelines.
  message: '{{error}}'
  severity: warn
  formats:
  - oas2
  given: $.paths[*][*].responses
  then:
    function: error-response
  x-status: draft
  x-tags:
      - Tag       