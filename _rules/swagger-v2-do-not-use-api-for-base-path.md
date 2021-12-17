---
swagger-v2-do-not-use-api-for-base-path:
  description: Ensures that paths do not use /api as part of the base path.
  message: You should not use /api as part of your base path.
  severity: warn
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: ^/api
...
swagger-v2-do-not-use-api-for-base-path:
  description: Ensures that paths do not use /api as part of the base path.
  message: You should not use /api as part of your base path.
  severity: warn
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      notMatch: ^/api
