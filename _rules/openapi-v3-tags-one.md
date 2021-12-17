---
openapi-v3-tags-one:
  description: Ensuring that there is at least on tag being applied.
  message: You should have at least one tag.
  given: $
  severity: error
  then:
    field: tags
    function: length
    functionOptions:
      min: 1
  type: style
...
openapi-v3-tags-one:
  description: Ensuring that there is at least on tag being applied.
  message: You should have at least one tag.
  given: $
  severity: error
  then:
    field: tags
    function: length
    functionOptions:
      min: 1
  type: style
