---
description: La URI no debe acabar en barra '/'.
severity: error
recommended: true
message: Check path ends without slashbar. {{value}} is not a valid path.
given: $.paths.
then:
  function: pattern
  functionOptions:
    match: ^.*[^/]$
...
description: La URI no debe acabar en barra '/'.
severity: error
recommended: true
message: Check path ends without slashbar. {{value}} is not a valid path.
given: $.paths.
then:
  function: pattern
  functionOptions:
    match: ^.*[^/]$