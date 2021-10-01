---
components-parameters-prefix-in-path:
  description: Parameters should be in a location matching the prefix (Path.)
  message: '{{value}} does not match the parameter prefix. {{description}}. Fix by
    assigning the correct in value, eg. header -> path.'
  given: $.components.parameters..[?(@property.match(/^Path\./))]
  severity: error
  then:
    field: in
    function: pattern
    functionOptions:
      match: ^path$
...
components-parameters-prefix-in-path:
  description: Parameters should be in a location matching the prefix (Path.)
  message: '{{value}} does not match the parameter prefix. {{description}}. Fix by
    assigning the correct in value, eg. header -> path.'
  given: $.components.parameters..[?(@property.match(/^Path\./))]
  severity: error
  then:
    field: in
    function: pattern
    functionOptions:
      match: ^path$