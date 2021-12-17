---
swagger-v2-schema-properties-names-words:
  description: Schema property names should not contain certain words.
  message: Schema property names should not contain the words word, word, and word.
  severity: error
  given: $.definitions.properties.*
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
swagger-v2-schema-properties-names-words:
  description: Schema property names should not contain certain words.
  message: Schema property names should not contain the words word, word, and word.
  severity: error
  given: $.definitions.properties.*
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
