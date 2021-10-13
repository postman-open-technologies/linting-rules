---
info-description-word-check:
  description: The API description must not contain specific words, including REST, Public, and Developer.
  given: "$.info.description"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
    function: pattern
    functionOptions:
      notMatch: \b(REST|Public|Developer)\b
  x-status: validated
  x-tags:
    - Info
    - Filters
    - Dictionaries
...
info-description-word-check:
  description: The API description must not contain specific words, including REST, Public, and Developer.
  given: "$.info.description"
  severity: error
  recommended: true
  type: style
  formats:
      - oas3
  then:
    function: pattern
    functionOptions:
      notMatch: \b(REST|Public|Developer)\b
  x-status: validated
  x-tags:
    - Info
    - Filters
    - Dictionaries  