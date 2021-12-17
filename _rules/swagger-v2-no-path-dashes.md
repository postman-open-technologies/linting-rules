---
swagger-v2-no-path-dashes:
  description: Ensures that paths do not contain dashes.
  message: Your paths should not contain dashes.
  severity: error
  recommended: true
  given: $.paths[*]~
  then:
    function: pattern
    functionOptions:
      notMatch: /-/
...
swagger-v2-no-path-dashes:
  description: Ensures that paths do not contain dashes.
  message: Your paths should not contain dashes.
  severity: error
  recommended: true
  given: $.paths[*]~
  then:
    function: pattern
    functionOptions:
      notMatch: /-/
