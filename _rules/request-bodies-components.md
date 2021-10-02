---
request-bodies-components:
  description: $ref may only point to examples or elements in the components section
    of openapi.yaml to generate good class names
  severity: error
  resolved: false
  given: $..requestBody..*.$ref
  then:
    function: pattern
    functionOptions:
      match: ^.*\#\/components\/schemas.*|examples.*$
  x-status: draft
  x-tags:
    - Tag        
...
request-bodies-components:
  description: $ref may only point to examples or elements in the components section
    of openapi.yaml to generate good class names
  severity: error
  resolved: false
  given: $..requestBody..*.$ref
  then:
    function: pattern
    functionOptions:
      match: ^.*\#\/components\/schemas.*|examples.*$
  x-status: draft
  x-tags:
    - Tag        