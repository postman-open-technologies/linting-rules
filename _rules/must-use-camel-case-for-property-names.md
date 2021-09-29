---
message: Property name has to be ASCII camelCase
description: MUST property names must be ASCII camelCase [118a]
documentationUrl: https://github.com/baloise-incubator/spectral-ruleset/blob/main/doc/rules/property-names-must-be-ascii-camel-case.md
severity: error
given: $.paths.*.*[responses,requestBody]..content..schema..properties.*~
then:
  function: pattern
  functionOptions:
    match: ^[a-z]+((\d)|([A-Z0-9][a-z0-9]+))*([A-Z])?$
...message: Property name has to be ASCII camelCase
description: MUST property names must be ASCII camelCase [118a]
documentationUrl: https://github.com/baloise-incubator/spectral-ruleset/blob/main/doc/rules/property-names-must-be-ascii-camel-case.md
severity: error
given: $.paths.*.*[responses,requestBody]..content..schema..properties.*~
then:
  function: pattern
  functionOptions:
    match: ^[a-z]+((\d)|([A-Z0-9][a-z0-9]+))*([A-Z])?$