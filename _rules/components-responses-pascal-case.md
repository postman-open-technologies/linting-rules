---
components-responses-pascal-case:
  description: All responses should be named with UpperCamelCase
  message: '{{property}} is not UpperCamelCase. {{description}}. Fix by renaming the
    definition, eg. object -> Object.'
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
      separator:
        char: .
        allowLeading: false
...
components-responses-pascal-case:
  description: All responses should be named with UpperCamelCase
  message: '{{property}} is not UpperCamelCase. {{description}}. Fix by renaming the
    definition, eg. object -> Object.'
  given: $.components.responses
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
      separator:
        char: .
        allowLeading: false