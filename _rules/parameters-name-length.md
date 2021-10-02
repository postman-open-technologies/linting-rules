---
parameters-name-length:
  description: Path and query parmeters must use camelCase.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: summary
    function: length
    functionOptions: 
      max: 20
  x-status: validated
  x-tags:
    - Parameters
    - Length        
...
parameters-name-length:
  description: Path and query parmeters must use camelCase.
  given: $.paths.*.*.parameters[?(@.in=='query')].name
  then:
    field: summary
    function: length
    functionOptions: 
      max: 20
  x-status: validated
  x-tags:
    - Parameters
    - Length        