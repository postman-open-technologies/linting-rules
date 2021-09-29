---
description: All header names should be Upper-Camel-Case
message: '''{{value}}'' is not Upper-Camel-Case. {{description}}. Fix by renaming
  the parameter, eg. headerName -> Header-Name.'
given: $.components.parameters..[?(@.in==='header')]
severity: warn
then:
  field: name
  function: casing
  functionOptions:
    type: pascal
    separator:
      char: '-'
      allowLeading: false
...description: All header names should be Upper-Camel-Case
message: '''{{value}}'' is not Upper-Camel-Case. {{description}}. Fix by renaming
  the parameter, eg. headerName -> Header-Name.'
given: $.components.parameters..[?(@.in==='header')]
severity: warn
then:
  field: name
  function: casing
  functionOptions:
    type: pascal
    separator:
      char: '-'
      allowLeading: false