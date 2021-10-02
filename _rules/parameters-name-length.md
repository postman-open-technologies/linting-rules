---
parameters-name-length:
  description: The name can't be more than 20 characters.
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
  description: The name can't be more than 20 characters.
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