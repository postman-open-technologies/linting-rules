---
swagger-v2-info-description-word-check:
  description: Ensures that all APIs descriptions do not contain certain words.
  message: >-
    The info object description cannot contain the words REST, public,
    developer.
  given: $.info.description
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    function: pattern
    functionOptions:
      notMatch: \b(REST|Public|Developer)\b
...
swagger-v2-info-description-word-check:
  description: Ensures that all APIs descriptions do not contain certain words.
  message: >-
    The info object description cannot contain the words REST, public,
    developer.
  given: $.info.description
  severity: error
  recommended: true
  type: style
  formats:
    - oas2
  then:
    function: pattern
    functionOptions:
      notMatch: \b(REST|Public|Developer)\b
