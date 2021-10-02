---
parameters-in:
  description: "Parameters must have an in."
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: in
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      
...
parameters-in:
  description: "Parameters must have an in."
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: in
    function: truthy
  x-status: validated
  x-tags:
    - Parameters     