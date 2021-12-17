---
openapi-v3-info-title-word-check:
  description: Ensures that all OpenAPIs info object title do not contain certain words.
  message: >-
    The info object title should not contain the words REST, Public, and
    Developer.
  given: $.info.title
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
openapi-v3-info-title-word-check:
  description: Ensures that all OpenAPIs info object title do not contain certain words.
  message: >-
    The info object title should not contain the words REST, Public, and
    Developer.
  given: $.info.title
  severity: error
  recommended: true
  type: style
  formats:
    - oas3
  then:
    function: pattern
    functionOptions:
      notMatch: \b(REST|Public|Developer)\b
