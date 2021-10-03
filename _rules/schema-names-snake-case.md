---
schema-names-snake-case:
  description: Schema names should be snake case.
  message: Schema name should be snake case.
  severity: hint
  formats:
  - oas2
  given: $.definitions.*~
  then:
    function: casing
    functionOptions:
      type: snake
  x-status: draft
  x-tags:
      - Tag          
...
schema-names-snake-case:
  description: Schema names should be snake case.
  message: Schema name should be snake case.
  severity: hint
  formats:
  - oas2
  given: $.definitions.*~
  then:
    function: casing
    functionOptions:
      type: snake
  x-status: draft
  x-tags:
      - Tag          