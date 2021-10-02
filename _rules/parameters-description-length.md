---
parameters-description-length:
  description: The description can't be more than 20 characters.
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
  description: The description can't be more than 20 characters.
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