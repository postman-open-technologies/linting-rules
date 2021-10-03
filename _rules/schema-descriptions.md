---
schema-descriptions:
  description: All schema should have a description.
  message: No description in {{property}}.
  severity: warn
  given: $components.schemas.properties.*
  then:
    field: description
    function: truthy
  x-status: draft
  x-tags:
      - Tag        
...
schema-descriptions:
  description: All schema should have a description.
  message: No description in {{property}}.
  severity: warn
  given: $components.schemas.properties.*
  then:
    field: description
    function: truthy
  x-status: draft
  x-tags:
      - Tag      