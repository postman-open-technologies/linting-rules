---
swagger-v2-have-get-method:
  description: Ensures that all APIs at least have one GET method.
  message: An API must have at least one GET method.
  formats:
    - oas2
  given: $.paths[/]
  severity: warn
  then:
    field: get
    function: truthy
...
swagger-v2-have-get-method:
  description: Ensures that all APIs at least have one GET method.
  message: An API must have at least one GET method.
  formats:
    - oas2
  given: $.paths[/]
  severity: warn
  then:
    field: get
    function: truthy
