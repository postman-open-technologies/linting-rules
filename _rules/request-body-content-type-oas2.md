---
request-body-content-type-oas2:
  description: The request body content type for patch operations should be JSON merge
    patch.
  message: '{{error}}'
  severity: warn
  formats:
  - oas2
  given: $
  then:
    function: patch-content-type
...
request-body-content-type-oas2:
  description: The request body content type for patch operations should be JSON merge
    patch.
  message: '{{error}}'
  severity: warn
  formats:
  - oas2
  given: $
  then:
    function: patch-content-type