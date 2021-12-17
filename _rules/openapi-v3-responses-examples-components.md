---
openapi-v3-responses-examples-components:
  description: >-
    Check response examples to ensure that they only have references to
    components.
  message: Response examples should only reference components.
  severity: error
  resolved: false
  given:
    - $..responses.*.content..*.examples.$ref
  then:
    function: pattern
    functionOptions:
      match: '#/components/'
...
openapi-v3-responses-examples-components:
  description: >-
    Check response examples to ensure that they only have references to
    components.
  message: Response examples should only reference components.
  severity: error
  resolved: false
  given:
    - $..responses.*.content..*.examples.$ref
  then:
    function: pattern
    functionOptions:
      match: '#/components/'
