---
swagger-v2-info-license-name:
  description: Ensures that all Swaggers have a information object license name.
  message: The info object should have a license name.
  given: $.info.license
  severity: error
  then:
    field: name
    function: truthy
...
swagger-v2-info-license-name:
  description: Ensures that all Swaggers have a information object license name.
  message: The info object should have a license name.
  given: $.info.license
  severity: error
  then:
    field: name
    function: truthy
