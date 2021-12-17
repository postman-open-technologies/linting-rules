---
swagger-v2-parameters-description-word-check:
  description: Ensures that some words aren't used in parameter descriptions.
  message: Your parameter descriptions can't contain the words word, word, and word.
  given: $.paths.*.*.parameters[?(@.in=='query')].description
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
swagger-v2-parameters-description-word-check:
  description: Ensures that some words aren't used in parameter descriptions.
  message: Your parameter descriptions can't contain the words word, word, and word.
  given: $.paths.*.*.parameters[?(@.in=='query')].description
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
