---
message: Path can contain correct URI versioning
description: CAN use correct URI versioning [115a]
documentationUrl: https://github.com/baloise-incubator/spectral-ruleset/blob/main/doc/rules/can-use-correct-URI-versioning.test.md
severity: error
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    match: ^((?!.*\/v\d+(\/.*)?\/v\d+)\/.*)$
...message: Path can contain correct URI versioning
description: CAN use correct URI versioning [115a]
documentationUrl: https://github.com/baloise-incubator/spectral-ruleset/blob/main/doc/rules/can-use-correct-URI-versioning.test.md
severity: error
given: $.paths.*~
then:
  function: pattern
  functionOptions:
    match: ^((?!.*\/v\d+(\/.*)?\/v\d+)\/.*)$