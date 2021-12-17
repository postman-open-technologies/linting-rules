---
openapi-v3-schema-properties-type:
  description: Ensuring that all schemas properties should have a type.
  message: All schema properties should have type property.
  severity: warn
  formats:
    - oas3
  given: $..properties.*
  then:
    field: type
    function: truthy
...
openapi-v3-schema-properties-type:
  description: Ensuring that all schemas properties should have a type.
  message: All schema properties should have type property.
  severity: warn
  formats:
    - oas3
  given: $..properties.*
  then:
    field: type
    function: truthy
