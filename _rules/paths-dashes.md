---
paths-dashes:
  description: Paths should not contain dashes.
  severity: error
  recommended: true
  message: "Paths cannot contain dashes {{property}}"
  given: $.paths[*]~
  then:
    function: pattern
    functionOptions:
      notMatch: /-/
  x-status: validated
  x-tags:
      - Paths          
...
paths-dashes:
  description: Paths should not contain dashes.
  severity: error
  recommended: true
  message: "Paths cannot contain dashes {{property}}"
  given: $.paths[*]~
  then:
    function: pattern
    functionOptions:
      notMatch: /-/
  x-status: validated
  x-tags:
      - Paths        