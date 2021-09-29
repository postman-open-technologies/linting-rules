---
description: response and requestBody content schema $ref may only point to elements
  in the components section of openapi.yaml to generate good class names
severity: error
resolved: false
given:
- $..responses.*.content..*.schema.$ref
- $..requestBody.content..*.schema.$ref
then:
  function: pattern
  functionOptions:
    match: '#/components/'
...description: response and requestBody content schema $ref may only point to elements
  in the components section of openapi.yaml to generate good class names
severity: error
resolved: false
given:
- $..responses.*.content..*.schema.$ref
- $..requestBody.content..*.schema.$ref
then:
  function: pattern
  functionOptions:
    match: '#/components/'