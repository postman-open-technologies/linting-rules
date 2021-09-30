---
schema-descriptions:
  severity: warn
  given: $..properties.*
  then:
    field: description
    function: truthy
...
schema-descriptions:
  severity: warn
  given: $..properties.*
  then:
    field: description
    function: truthy