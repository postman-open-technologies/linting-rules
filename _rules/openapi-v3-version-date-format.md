---
openapi-v3-version-date-format:
  description: Ensuring that there is a data form version applied.
  message: You need to have a date version format.
  severity: error
  recommended: true
  given: $.info.version
  then:
    function: pattern
    functionOptions:
      match: ^([0-9]{4}-[0-9]{2}-[0-9]{2})$
...
openapi-v3-version-date-format:
  description: Ensuring that there is a data form version applied.
  message: You need to have a date version format.
  severity: error
  recommended: true
  given: $.info.version
  then:
    function: pattern
    functionOptions:
      match: ^([0-9]{4}-[0-9]{2}-[0-9]{2})$
