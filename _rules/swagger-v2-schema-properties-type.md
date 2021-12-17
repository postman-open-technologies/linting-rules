---
swagger-v2-schema-properties-type:
  description: Ensuring that all schemas properties should have a type.
  message: All schema properties should have type property.
  severity: warn
  formats:
    - oas2
  given: $.definitions.properties.*
  then:
    field: type
    function: truthy
...
swagger-v2-schema-properties-type:
  description: Ensuring that all schemas properties should have a type.
  message: All schema properties should have type property.
  severity: warn
  formats:
    - oas2
  given: $.definitions.properties.*
  then:
    field: type
    function: truthy
