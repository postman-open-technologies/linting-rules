---
swagger-v2-schema-names-words:
  description: Schema names should not contain certain words.
  message: Schema property names not contains the words word, word, and word.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
swagger-v2-schema-names-words:
  description: Schema names should not contain certain words.
  message: Schema property names not contains the words word, word, and word.
  severity: error
  given: $.definitions
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
