---
schema-names-pascal-case:
  description: Schema names should be Pascal case.
  message: Schema name should be Pascal case.
  severity: hint
  formats:
  - oas2
  given: $.definitions.*~
  then:
    function: casing
    functionOptions:
      type: pascal
  x-status: draft
  x-tags:
      - Tag          
...
schema-names-pascal-case:
  description: Schema names should be Pascal case.
  message: Schema name should be Pascal case.
  severity: hint
  formats:
  - oas2
  given: $.definitions.*~
  then:
    function: casing
    functionOptions:
      type: pascal
  x-status: draft
  x-tags:
      - Tag          