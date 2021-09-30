---
x-tags:
- it
description: |-
  When you design a REST API, you don't usually need to mention terms like
  `get`, `delete` and so on in your `paths`, because this information is
  conveyed by the HTTP method.
message: API "path" contains a name of an http method. {{error}}
severity: hint
recommended: true
given:
- $.paths[?(@property.match( /\/(get|post|put|delete|patch)[\/A-Z_\-]?/ ))]~
- $.paths[?(@property.match( /\/(create|remove|list)[\/A-Z_\-]?/ ))]~
then:
  field: '@key'
  function: undefined
...
x-tags:
- it
description: |-
  When you design a REST API, you don't usually need to mention terms like
  `get`, `delete` and so on in your `paths`, because this information is
  conveyed by the HTTP method.
message: API "path" contains a name of an http method. {{error}}
severity: hint
recommended: true
given:
- $.paths[?(@property.match( /\/(get|post|put|delete|patch)[\/A-Z_\-]?/ ))]~
- $.paths[?(@property.match( /\/(create|remove|list)[\/A-Z_\-]?/ ))]~
then:
  field: '@key'
  function: undefined