---
openapi-v3-no-trailing-slash-on-paths:
  description: Ensures that there are no trailing slashes on paths.
  message: There should be no trailing slashes on paths.
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: /$
...
openapi-v3-no-trailing-slash-on-paths:
  description: Ensures that there are no trailing slashes on paths.
  message: There should be no trailing slashes on paths.
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: /$
