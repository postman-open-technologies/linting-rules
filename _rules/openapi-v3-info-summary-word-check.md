---
openapi-v3-info-summary-word-check:
  description: >-
    Ensures that all OpenAPIs information object summary do not contain some
    words.
  message: >-
    The info object summary should not contain the words REST, Public, or
    Developer.
  given: $.info.summary
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    function: pattern
    functionOptions:
      notMatch: \b(REST|Public|Developer)\b
...
openapi-v3-info-summary-word-check:
  description: >-
    Ensures that all OpenAPIs information object summary do not contain some
    words.
  message: >-
    The info object summary should not contain the words REST, Public, or
    Developer.
  given: $.info.summary
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    function: pattern
    functionOptions:
      notMatch: \b(REST|Public|Developer)\b
