---
severity: error
message: '`{{value}}` must follow `snake` notation'
given: $..parameters[?(@.in == 'query' || @ == 'path')].name
then:
  function: casing
  functionOptions:
    type: snake
...
message: '`{{value}}` must follow `snake` notation'
given: $..parameters[?(@.in == 'query' || @ == 'path')].name
then:
  function: casing
  functionOptions:
    type: snake