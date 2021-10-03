---
schema-names-words:
  description: Schema names should not contain certain words.
  message: Should not contains certain words {{ parameter }}.
  severity: error
  given: $.components.schemas
  then:
    field: "@key"
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  x-status: validated
  x-tags:
      - Schema
      - Words          
...
schema-names-words:
  description: Schema names should not contain certain words.
  message: Should not contains certain words {{ parameter }}.
  severity: error
  given: $.components.schemas
  then:
    field: "@key"
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  x-status: validated
  x-tags:
      - Schema
      - Words      