---
description: $ref may only point to examples or elements in the components section
  of openapi.yaml to generate good class names
severity: error
resolved: false
given: $..responses..*.$ref
then:
  function: pattern
  functionOptions:
    match: ^.*\#\/components\/schemas.*|examples.*$
...
description: $ref may only point to examples or elements in the components section
  of openapi.yaml to generate good class names
severity: error
resolved: false
given: $..responses..*.$ref
then:
  function: pattern
  functionOptions:
    match: ^.*\#\/components\/schemas.*|examples.*$