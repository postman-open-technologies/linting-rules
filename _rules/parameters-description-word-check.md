---
parameters-description-word-check:
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: $.paths.*.*.parameters[?(@.in=='query')].description
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  x-status: validated
  x-tags:
    - Parameters
    - Words        
...
parameters-description-word-check:
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: $.paths.*.*.parameters[?(@.in=='query')].description
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  x-status: validated
  x-tags:
    - Parameters
    - Words       