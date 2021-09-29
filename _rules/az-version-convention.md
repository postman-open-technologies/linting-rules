---
description: API version should be a date in YYYY-MM-DD format, optionally suffixed
  with '-preview'.
severity: error
formats:
- oas2
- oas3
given: $.info.version
then:
  function: pattern
  functionOptions:
    match: ^\\d\\d\\d\\d-\\d\\d-\\d\\d(-preview)?$
...description: API version should be a date in YYYY-MM-DD format, optionally suffixed
  with '-preview'.
severity: error
formats:
- oas2
- oas3
given: $.info.version
then:
  function: pattern
  functionOptions:
    match: ^\\d\\d\\d\\d-\\d\\d-\\d\\d(-preview)?$