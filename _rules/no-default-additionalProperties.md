---
description: |-
  By default, jsonschema allows additionalProperties. This means
  that schema validators can be bypassed using further, unspecified
  fields.
message: 'Objects should not allow additionalProperties. Disable them with `additionalProperties:
  false` or constraint them.'
formats:
- oas3
severity: warn
recommended: true
given:
- $.[?(@.type=="object" && ! @.additionalProperties)]
then:
- field: additionalProperties
  function: defined
...
description: |-
  By default, jsonschema allows additionalProperties. This means
  that schema validators can be bypassed using further, unspecified
  fields.
message: 'Objects should not allow additionalProperties. Disable them with `additionalProperties:
  false` or constraint them.'
formats:
- oas3
severity: warn
recommended: true
given:
- $.[?(@.type=="object" && ! @.additionalProperties)]
then:
- field: additionalProperties
  function: defined