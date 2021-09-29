---
description: By default, jsonschema allows additionalProperties. This means
  that schema validators can be bypassed using further, unspecified
  fields. While forbidding additionalProperties can create rigidity and hinder
  the evolution of an API - eg making it hard to accept new parameters
  or fields - it is possible that this flexibility can be used
  to bypass the schema validator and force the application to process
  unwanted information.
message: 'Objects should not allow additionalProperties. Disable them with `additionalProperties:
  false` or constraint them.'
formats:
- oas3
severity: warn
recommended: true
given:
- $.[?(@.type=="object" && @.additionalProperties &&  @.additionalProperties!=true
  &&  @.additionalProperties!=false )]
then:
- field: maxProperties
  function: defined
...
description: By default, jsonschema allows additionalProperties. This means
  that schema validators can be bypassed using further, unspecified
  fields. While forbidding additionalProperties can create rigidity and hinder
  the evolution of an API - eg making it hard to accept new parameters
  or fields - it is possible that this flexibility can be used
  to bypass the schema validator and force the application to process
  unwanted information.
message: 'Objects should not allow additionalProperties. Disable them with `additionalProperties:
  false` or constraint them.'
formats:
- oas3
severity: warn
recommended: true
given:
- $.[?(@.type=="object" && @.additionalProperties &&  @.additionalProperties!=true
  &&  @.additionalProperties!=false )]
then:
- field: maxProperties
  function: defined