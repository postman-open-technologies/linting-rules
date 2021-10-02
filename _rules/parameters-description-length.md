---
parameters-description-length:
  description: Path and query parmeters must use camelCase.
  given: $.paths.*.*.parameters[?(@.in=='query')].description
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
parameters-description-length:
  description: Path and query parmeters must use camelCase.
  given: $.paths.*.*.parameters[?(@.in=='query')].description
  then:
    field: summary
    function: length
    functionOptions: 
      max: 20
  x-status: validated
  x-tags:
    - Parameters
    - Length        