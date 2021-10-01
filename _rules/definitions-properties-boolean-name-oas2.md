---
definitions-properties-boolean-name-oas2:
  description: Checks for specific pattern in boolean property names.
  severity: error
  message: CONT03 Invalid property name for boolean type {{value}} (boolean may start with is or has and followed by capital letter or number to be more descriptive. expected isErased, hasStock)
  recommended: true
  given: $.definitions.*.properties..[?(@.type=='boolean')]~
  then:
    function: pattern
    functionOptions:
      match: ^(is|has)[A-Z0-9][a-zA-Z0-9]*
  x-status: draft
  x-tags:
    - Tag      
...
definitions-properties-boolean-name-oas2:
  description: Checks for specific pattern in boolean property names.
  severity: error
  message: CONT03 Invalid property name for boolean type {{value}} (boolean may start with is or has and followed by capital letter or number to be more descriptive. expected isErased, hasStock)
  recommended: true
  given: $.definitions.*.properties..[?(@.type=='boolean')]~
  then:
    function: pattern
    functionOptions:
      match: ^(is|has)[A-Z0-9][a-zA-Z0-9]*
  x-status: draft
  x-tags:
    - Tag      