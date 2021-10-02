---
parameters-name-pascal-case:
  description: Path and query parmeters must use PascalCase.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: name
    function: casing
    functionOptions:
      type: pascal
  x-status: validated
  x-tags:
    - Parameters
    - Casing      
...
parameters-name-pascal-case:
  description: Path and query parmeters must use PascalCase.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: name
    function: casing
    functionOptions:
      type: pascal
  x-status: validated
  x-tags:
    - Parameters
    - Casing        