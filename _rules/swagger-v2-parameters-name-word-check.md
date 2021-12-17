---
swagger-v2-parameters-name-word-check:
  description: Ensures that that all some words aren't used for parameter names.
  message: Your parameter names should not contain the words word, word, and word.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
swagger-v2-parameters-name-word-check:
  description: Ensures that that all some words aren't used for parameter names.
  message: Your parameter names should not contain the words word, word, and word.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
