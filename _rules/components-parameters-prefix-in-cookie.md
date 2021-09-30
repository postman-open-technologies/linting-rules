---
components-parameters-prefix-in-cookie:
  description: Parameters should be in a location matching the prefix (Cookie.)
  message: '{{value}} does not match the parameter prefix. {{description}}. Fix by
    assigning the correct in value, eg. header -> cookie.'
  given: $.components.parameters..[?(@property.match(/^Cookie\./))]
  severity: error
  then:
    field: in
    function: pattern
    functionOptions:
      match: ^cookie$
...
components-parameters-prefix-in-cookie:
  description: Parameters should be in a location matching the prefix (Cookie.)
  message: '{{value}} does not match the parameter prefix. {{description}}. Fix by
    assigning the correct in value, eg. header -> cookie.'
  given: $.components.parameters..[?(@property.match(/^Cookie\./))]
  severity: error
  then:
    field: in
    function: pattern
    functionOptions:
      match: ^cookie$