---
severity: warn
description: Prefer `application/merge-patch+json` for `PATCH` requests
given: $.paths.*.[?(@property == 'patch')].requestBody.content
then:
  function: contains
  functionOptions:
    match: application/merge-patch\+json
...severity: warn
description: Prefer `application/merge-patch+json` for `PATCH` requests
given: $.paths.*.[?(@property == 'patch')].requestBody.content
then:
  function: contains
  functionOptions:
    match: application/merge-patch\+json