---
response-status-204-no-body:
  severity: error
  description: 204 response should have no body. Use e.g. 200 otherwise.
  given: $..responses.204
  then:
    field: content
    function: falsy
...
response-status-204-no-body:
  severity: error
  description: 204 response should have no body. Use e.g. 200 otherwise.
  given: $..responses.204
  then:
    field: content
    function: falsy