---
schema-names-camel-case:
  description: Schema names should be camel case.
  message: Schema name should be camel case.
  severity: hint
  formats:
  - oas2
  given: $.definitions.*~
  then:
    function: casing
    functionOptions:
      type: camel
  x-status: draft
  x-tags:
      - Tag          
...
schema-names-camel-case:
  description: Schema names should be camel case.
  message: Schema name should be camel case.
  severity: hint
  formats:
  - oas2
  given: $.definitions.*~
  then:
    function: casing
    functionOptions:
      type: camel
  x-status: draft
  x-tags:
      - Tag          