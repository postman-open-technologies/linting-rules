---
openapi-v3-schema-names-words:
  description: Schema names should not contain certain words.
  message: Schema property names not contains the words word, word, and word.
  severity: error
  given: $.components.schemas
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
openapi-v3-schema-names-words:
  description: Schema names should not contain certain words.
  message: Schema property names not contains the words word, word, and word.
  severity: error
  given: $.components.schemas
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
