---
parameters-name:
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: name
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      
...
parameters-name:
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: name
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      