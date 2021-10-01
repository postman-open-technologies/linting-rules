---
version-date-format:
  severity: error
  recommended: true
  message: Specs should follow inception date based versioning eg. 2020-01-01. {{value}}
    is not a valid version.
  given: $.info.version
  then:
    function: pattern
    functionOptions:
      match: ^([0-9]{4}-[0-9]{2}-[0-9]{2})$
...
version-date-format:
  severity: error
  recommended: true
  message: Specs should follow inception date based versioning eg. 2020-01-01. {{value}}
    is not a valid version.
  given: $.info.version
  then:
    function: pattern
    functionOptions:
      match: ^([0-9]{4}-[0-9]{2}-[0-9]{2})$