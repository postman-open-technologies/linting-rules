---
parameters-description:
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: description
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      
...
parameters-description:
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: description
    function: truthy
  x-status: validated
  x-tags:
    - Parameters      