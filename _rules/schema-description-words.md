---
schema-description-words:
  description: Some words should not be be contained within the schema description.
  message: Words should not be contained within description {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $.components.schemas.*
  then:
      field: description
        function: pattern
        functionOptions:
        notMatch: \b(word|word|word)\b
  x-status: validated
  x-tags:
      - Schema         
...
schema-description-words:
  description: Some words should not be be contained within the schema description.
  message: Words should not be contained within description {{ property }}.
  severity: warn
  formats:
  - oas3
  given: $.components.schemas.*
  then:
      field: description
        function: pattern
        functionOptions:
        notMatch: \b(word|word|word)\b
  x-status: validated
  x-tags:
      - Schema  