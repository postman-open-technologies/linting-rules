---
description: Security schemes should be prefixed with their security type (Oidc. Csh.
  or Keys.)
message: '''{{property}}'' is not prefixed properly. {{description}}. Fix by renaming
  the parameter definition, eg. AccessToken -> Oidc.AccessToken.'
given: $.components.securitySchemes
severity: warn
then:
  field: '@key'
  function: pattern
  functionOptions:
    match: ^Keys\.|^Oidc\.|^Csh\.
...
  or Keys.)
message: '''{{property}}'' is not prefixed properly. {{description}}. Fix by renaming
  the parameter definition, eg. AccessToken -> Oidc.AccessToken.'
given: $.components.securitySchemes
severity: warn
then:
  field: '@key'
  function: pattern
  functionOptions:
    match: ^Keys\.|^Oidc\.|^Csh\.