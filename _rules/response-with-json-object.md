---
description: |-
  JSON responses MUST use JSON objects, in order to be extensible. This allows the schema to evolve in a backward compatible ways.
message: JSON responses must use json objects (eg "{}"), not {{value}}. {{path}}
severity: warn
recommended: true
given: $.[responses][*][content][?(@property.match("json$"))][schema]
then:
  field: type
  function: pattern
  functionOptions:
    match: object
...
description: |-
  JSON responses MUST use JSON objects, in order to be extensible. This allows the schema to evolve in a backward compatible ways.
message: JSON responses must use json objects (eg "{}"), not {{value}}. {{path}}
severity: warn
recommended: true
given: $.[responses][*][content][?(@property.match("json$"))][schema]
then:
  field: type
  function: pattern
  functionOptions:
    match: object