---
openapi-v3-schema-properties-descriptions-words:
  description: Some words should not exist within the property description.
  message: >-
    Schema property descriptions should not contain the words word, word, and
    word.
  severity: warn
  formats:
    - oas3
  given: $..properties.*
  then:
    field: description
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
openapi-v3-schema-properties-descriptions-words:
  description: Some words should not exist within the property description.
  message: >-
    Schema property descriptions should not contain the words word, word, and
    word.
  severity: warn
  formats:
    - oas3
  given: $..properties.*
  then:
    field: description
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
