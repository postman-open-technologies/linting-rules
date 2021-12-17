---
openapi-v3-operations-description-words-check:
  description: Ensures that the description do not contain certain words.
  message: Your operation descriptions should not use the words word, word, and word.
  given: $.paths.*[get,post,patch,put,delete].description
  recommended: true
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  type: style
...
openapi-v3-operations-description-words-check:
  description: Ensures that the description do not contain certain words.
  message: Your operation descriptions should not use the words word, word, and word.
  given: $.paths.*[get,post,patch,put,delete].description
  recommended: true
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  type: style
