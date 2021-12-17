---
openapi-v3-schema-properties-descriptions:
  description: Ensure that all schemas properties should have a description.
  message: All schema properties should have descriptions.
  severity: warn
  formats:
    - oas3
  given: $..properties.*
  then:
    field: description
    function: truthy
...
openapi-v3-schema-properties-descriptions:
  description: Ensure that all schemas properties should have a description.
  message: All schema properties should have descriptions.
  severity: warn
  formats:
    - oas3
  given: $..properties.*
  then:
    field: description
    function: truthy
