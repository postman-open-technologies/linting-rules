---
schema-should-have-description-or-title-oas3:
  description: All schemas should have a description or title.
  message: Schema should have a description or title.
  severity: warn
  formats:
  - oas2
  - oas3
  given:
  - $.definitions[?(!@.description && !@.title)]
  - $.components.schemas[?(!@.description && !@.title)]
  then:
    function: falsy
...
schema-should-have-description-or-title-oas3:
  description: All schemas should have a description or title.
  message: Schema should have a description or title.
  severity: warn
  formats:
  - oas2
  - oas3
  given:
  - $.definitions[?(!@.description && !@.title)]
  - $.components.schemas[?(!@.description && !@.title)]
  then:
    function: falsy