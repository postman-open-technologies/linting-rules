---
info-license-url:
  description: API must have a license url applied.
  given: $.info.license
  severity: error
  then:
    field: url
    function: truthy
  x-status: validated
  x-tags:
    - License
    - Legal     
...
info-license-url:
  description: API must have a license url applied.
  given: $.info.license
  severity: error
  then:
    field: url
    function: truthy
  x-status: validated
  x-tags:
    - License
    - Legal 