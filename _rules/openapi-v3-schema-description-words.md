---
openapi-v3-schema-description-words:
  description: Some words should not be be contained within the schema description.
  message: Do not use the words word, word, and word in the schema descriptions.
  severity: warn
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: description
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
openapi-v3-schema-description-words:
  description: Some words should not be be contained within the schema description.
  message: Do not use the words word, word, and word in the schema descriptions.
  severity: warn
  formats:
    - oas3
  given: $.components.schemas.*
  then:
    field: description
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
