---
response-pagination-response-oas2:
  description: An operation that returns a list that is potentially large should support
    pagination.
  message: '{{error}}'
  severity: warn
  formats:
  - oas2
  given:
  - $.paths.*[get,post]
  then:
    function: pagination-response
...
response-pagination-response-oas2:
  description: An operation that returns a list that is potentially large should support
    pagination.
  message: '{{error}}'
  severity: warn
  formats:
  - oas2
  given:
  - $.paths.*[get,post]
  then:
    function: pagination-response