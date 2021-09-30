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