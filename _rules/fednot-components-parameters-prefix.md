---
description: Parameters should be prefixed with their parameter type (Header. Cookie.
  Query. or Path.)
message: '''{{property}}'' is not prefixed properly. {{description}}. Fix by renaming
  the parameter definition, eg. Parameter -> Header.Parameter.'
given: $.components.parameters
severity: warn
then:
  field: '@key'
  function: pattern
  functionOptions:
    match: ^Header\.|^Cookie\.|^Query\.|^Path\.
...description: Parameters should be prefixed with their parameter type (Header. Cookie.
  Query. or Path.)
message: '''{{property}}'' is not prefixed properly. {{description}}. Fix by renaming
  the parameter definition, eg. Parameter -> Header.Parameter.'
given: $.components.parameters
severity: warn
then:
  field: '@key'
  function: pattern
  functionOptions:
    match: ^Header\.|^Cookie\.|^Query\.|^Path\.