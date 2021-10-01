---
components-callbacks-camelcase:
  description: All callbacks should be named with UpperCamelCase
  message: '{{property}} is not UpperCamelCase. {{description}}. Fix by renaming the
    callback, eg. object -> Object.'
  given: $.components.callbacks
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
      separator:
        char: .
        allowLeading: false
  x-status: draft
  x-tags:
    - Tag        
...
components-callbacks-camelcase:
  description: All callbacks should be named with UpperCamelCase
  message: '{{property}} is not UpperCamelCase. {{description}}. Fix by renaming the
    callback, eg. object -> Object.'
  given: $.components.callbacks
  severity: error
  then:
    field: '@key'
    function: casing
    functionOptions:
      type: pascal
      separator:
        char: .
        allowLeading: false
  x-status: draft
  x-tags:
    - Tag        