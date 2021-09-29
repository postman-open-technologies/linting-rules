---
description: APIs MUST have a root path defined (`/`), to stop forcing all API consumers
  to visit documentation for basic interactions.
severity: warn
given: $.paths
then:
  field: /
  function: truthy
...description: APIs MUST have a root path defined (`/`), to stop forcing all API consumers
  to visit documentation for basic interactions.
severity: warn
given: $.paths
then:
  field: /
  function: truthy