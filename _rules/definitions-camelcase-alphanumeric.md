---
definitions-camelcase-alphanumeric:
  description: All YAML/JSON definitions MUST follow fields-camelCase and be ASCII
    alphanumeric characters or _ or $.
  given: $.definitions[*]~
  message: '{{property}} MUST follow camelCase and be ASCII alphanumeric characters
    or _ or $.'
  recommended: true
  severity: error
  then:
    function: pattern
    functionOptions:
      match: /^[a-z$_]{1}[A-Z09$_]*/
  x-tags:
    - Adidas
...
definitions-camelcase-alphanumeric:
  description: All YAML/JSON definitions MUST follow fields-camelCase and be ASCII
    alphanumeric characters or _ or $.
  given: $.definitions[*]~
  message: '{{property}} MUST follow camelCase and be ASCII alphanumeric characters
    or _ or $.'
  recommended: true
  severity: error
  then:
    function: pattern
    functionOptions:
      match: /^[a-z$_]{1}[A-Z09$_]*/
  x-tags:
    - Adidas