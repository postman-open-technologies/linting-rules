---
openapi-v3-have-get-method:
  description: Ensures that all APIs at least have one GET method.
  message: An API must have at least one GET method.
  formats:
    - oas3
  given: $.paths[/]
  severity: warn
  then:
    field: get
    function: truthy
...
openapi-v3-have-get-method:
  description: Ensures that all APIs at least have one GET method.
  message: An API must have at least one GET method.
  formats:
    - oas3
  given: $.paths[/]
  severity: warn
  then:
    field: get
    function: truthy
