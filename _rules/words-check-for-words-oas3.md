---
words-check-for-words-oas3:
  description: Check for a specific set of words across descriptions.
  severity: warn
  message: Invalid property value {{value}} -- these words are not allowed
  recommended: true
  resolved: false
  given:
  - $.info..description
  - $.paths..description
  - $.parameters..description
  - $.definitions..description
  - $.info..title
  - $.info..name
  - $.tags..name
  - $.parameters..name
  - $.paths..summary
  - $.paths..operationId
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
...
words-check-for-words-oas3:
  description: Check for a specific set of words across descriptions.
  severity: warn
  message: Invalid property value {{value}} -- these words are not allowed
  recommended: true
  resolved: false
  given:
  - $.info..description
  - $.paths..description
  - $.parameters..description
  - $.definitions..description
  - $.info..title
  - $.info..name
  - $.tags..name
  - $.parameters..name
  - $.paths..summary
  - $.paths..operationId
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b