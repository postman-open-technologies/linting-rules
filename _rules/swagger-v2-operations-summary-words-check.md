---
swagger-v2-operations-summary-words-check:
  description: Ensures that each of the operations summaries do not content certain words.
  message: Your operations summaries should not contain the words word, word, and word.
  given: $.paths.*[get,post,patch,put,delete].summary
  recommended: true
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  type: style
...
swagger-v2-operations-summary-words-check:
  description: Ensures that each of the operations summaries do not content certain words.
  message: Your operations summaries should not contain the words word, word, and word.
  given: $.paths.*[get,post,patch,put,delete].summary
  recommended: true
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  type: style
