---
description: All models MUST have a valid example.
severity: error
recommended: true
formats:
- oas2
message: '{{ property }} MUST have a valid example.'
given: $..parameters..[?(@.in == 'body' && (@.example || @.schema.$ref))]
then:
  function: truthy
...description: All models MUST have a valid example.
severity: error
recommended: true
formats:
- oas2
message: '{{ property }} MUST have a valid example.'
given: $..parameters..[?(@.in == 'body' && (@.example || @.schema.$ref))]
then:
  function: truthy