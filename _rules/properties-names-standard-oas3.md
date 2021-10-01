---
properties-names-standard-oas3:
  description: Property names should be camel case.
  message: Property name should be camel case.
  severity: warn
  resolved: false
  given: $..[?(@.type === 'object' && @.properties)].properties.*~
  then:
    function: casing
    functionOptions:
      type: camel
...
properties-names-standard-oas3:
  description: Property names should be camel case.
  message: Property name should be camel case.
  severity: warn
  resolved: false
  given: $..[?(@.type === 'object' && @.properties)].properties.*~
  then:
    function: casing
    functionOptions:
      type: camel