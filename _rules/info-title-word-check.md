---
info-title-word-check:
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: "$.info.title"
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
info-title-word-check:
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: "$.info.title"
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