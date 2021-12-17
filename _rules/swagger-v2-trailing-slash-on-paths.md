---
swagger-v2-trailing-slash-on-paths:
  description: Ensures that there are trailing slashes on paths.
  message: There should be trailing slashes on paths.
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      match: /$
...
swagger-v2-trailing-slash-on-paths:
  description: Ensures that there are trailing slashes on paths.
  message: There should be trailing slashes on paths.
  severity: error
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      match: /$
