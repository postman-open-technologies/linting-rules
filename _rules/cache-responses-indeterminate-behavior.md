---
description: |-
  Cache usage SHOULD be extensively detailed in the `description` property
  to avoid data leaks or the usage of stale data.
message: '{{error}}'
formats:
- oas3
severity: info
recommended: true
given: $.[responses][?(@property[0] == "2" )][headers]
then:
- function: xor
  functionOptions:
    properties:
    - Expires
    - Cache-Control
...
description: |-
  Cache usage SHOULD be extensively detailed in the `description` property
  to avoid data leaks or the usage of stale data.
message: '{{error}}'
formats:
- oas3
severity: info
recommended: true
given: $.[responses][?(@property[0] == "2" )][headers]
then:
- function: xor
  functionOptions:
    properties:
    - Expires
    - Cache-Control