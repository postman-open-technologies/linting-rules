---
swagger-v2-no-trailing-slash-on-paths:
  description: Ensures that there are no trailing slashes on paths.
  message: There should be no trailing slashes on paths.
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: /$
...
swagger-v2-no-trailing-slash-on-paths:
  description: Ensures that there are no trailing slashes on paths.
  message: There should be no trailing slashes on paths.
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: /$
