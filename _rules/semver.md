---
severity: error
recommended: true
message: Specs should follow semantic versioning. {{value}} is not a valid version.
given: $.info.version
then:
  function: pattern
  functionOptions:
    match: ^([0-9]+.[0-9]+.[0-9]+)$
...severity: error
recommended: true
message: Specs should follow semantic versioning. {{value}} is not a valid version.
given: $.info.version
then:
  function: pattern
  functionOptions:
    match: ^([0-9]+.[0-9]+.[0-9]+)$