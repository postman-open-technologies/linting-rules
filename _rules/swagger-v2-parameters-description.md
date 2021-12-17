---
swagger-v2-parameters-description:
  description: Ensures that that all parameters have a descriptions.
  message: Your parameters all need descriptions.
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: description
    function: truthy
...
swagger-v2-parameters-description:
  description: Ensures that that all parameters have a descriptions.
  message: Your parameters all need descriptions.
  given: $.paths.*.*.parameters[?(@.in=='query')]
  then:
    field: description
    function: truthy
