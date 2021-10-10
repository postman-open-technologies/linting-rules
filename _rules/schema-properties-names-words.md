---
schema-properties-names-words:
  description: Schema property names should not contain certain words.
  message: Should not contains certain words {{ parameter }}.
  severity: error
  given: $..properties.*
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
schema-properties-names-words:
  description: Schema property names should not contain certain words.
  message: Should not contains certain words {{ parameter }}.
  severity: error
  given: $..properties.*
  then:
    field: "@key"
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  x-status: validated
  x-tags:
      - Schema
      - Words    