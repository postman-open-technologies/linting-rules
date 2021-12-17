---
openapi-v3-schema-properties-names-words:
  description: Schema property names should not contain certain words.
  message: Schema property names should not contain the words word, word, and word.
  severity: error
  given: $..properties.*
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
openapi-v3-schema-properties-names-words:
  description: Schema property names should not contain certain words.
  message: Schema property names should not contain the words word, word, and word.
  severity: error
  given: $..properties.*
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
