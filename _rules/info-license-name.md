---
info-license-name:
  description: Should have a license name.
  given: $.info.license
  severity: error
  then:
    field: name
    function: truthy
  x-status: validated
  x-tags:
    - License
    - Legal    
...
info-license-name:
  description: Should have a license name.
  given: $.info.license
  severity: error
  then:
    field: name
    function: truthy
  x-status: validated
  x-tags:
    - License
    - Legal     