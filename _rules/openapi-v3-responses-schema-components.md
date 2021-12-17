---
openapi-v3-responses-schema-components:
  description: >-
    Check response schema to ensure that they only have references to
    components.
  message: Response schema should only reference components.
  severity: error
  resolved: false
  given:
    - $..responses.*.content..*.schema.$ref
  then:
    function: pattern
    functionOptions:
      match: '#/components/'
...
openapi-v3-responses-schema-components:
  description: >-
    Check response schema to ensure that they only have references to
    components.
  message: Response schema should only reference components.
  severity: error
  resolved: false
  given:
    - $..responses.*.content..*.schema.$ref
  then:
    function: pattern
    functionOptions:
      match: '#/components/'
