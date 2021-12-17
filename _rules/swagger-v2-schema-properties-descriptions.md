---
swagger-v2-schema-properties-descriptions:
  description: Ensure that all schemas properties should have a description.
  message: All schema properties should have descriptions.
  severity: warn
  formats:
    - oas2
  given: $.definitions.properties.*
  then:
    field: description
    function: truthy
...
swagger-v2-schema-properties-descriptions:
  description: Ensure that all schemas properties should have a description.
  message: All schema properties should have descriptions.
  severity: warn
  formats:
    - oas2
  given: $.definitions.properties.*
  then:
    field: description
    function: truthy
