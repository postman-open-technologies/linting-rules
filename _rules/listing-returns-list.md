---
severity: warn
message: Type "{{value}}" should be "array" when returning a list of resources
given: $.paths.[?(!@property.toString().includes("}"))].get.responses.[?(@property.toString().startsWith("2"))].content.*.schema
then:
  field: type
  function: enumeration
  functionOptions:
    values:
    - array
...severity: warn
message: Type "{{value}}" should be "array" when returning a list of resources
given: $.paths.[?(!@property.toString().includes("}"))].get.responses.[?(@property.toString().startsWith("2"))].content.*.schema
then:
  field: type
  function: enumeration
  functionOptions:
    values:
    - array