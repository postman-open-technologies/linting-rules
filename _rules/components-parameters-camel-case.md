---
components-parameters-camel-case:
  description: All parameter names should be lowerCamelCase
  message: '{{value}} is not lowerCamelCase. {{description}}. Fix by renaming the
    parameter, eg. ParameterName -> parameterName.'
  given: $.components.parameters..[?(@.in==='query' || @.in==='path' || @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: camel
  x-status: draft
  x-tags:
    - Tag      
...
components-parameters-camel-case:
  description: All parameter names should be lowerCamelCase
  message: '{{value}} is not lowerCamelCase. {{description}}. Fix by renaming the
    parameter, eg. ParameterName -> parameterName.'
  given: $.components.parameters..[?(@.in==='query' || @.in==='path' || @.in==='cookie')]
  severity: warn
  then:
    field: name
    function: casing
    functionOptions:
      type: camel
  x-status: draft
  x-tags:
    - Tag      