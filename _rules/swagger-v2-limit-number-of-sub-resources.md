---
swagger-v2-limit-number-of-sub-resources:
  description: Ensures that there are not too many sub-resources.
  message: There should be no more than three levels of sub-resources.
  severity: warn
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      match: ^/[^/]*((/{[^}]*})*/[^/]*(/{[^}]*})*){0,3}/?$
...
swagger-v2-limit-number-of-sub-resources:
  description: Ensures that there are not too many sub-resources.
  message: There should be no more than three levels of sub-resources.
  severity: warn
  given: $.paths.*~
  then:
    function: pattern
    functionOptions:
      match: ^/[^/]*((/{[^}]*})*/[^/]*(/{[^}]*})*){0,3}/?$
