---
openapi-v3-operations-tags-one:
  description: Ensures that each of the operations have at least one tag.
  message: All of your operations need to have at least one tag.
  given: $
  severity: error
  then:
    field: tags
    function: length
    functionOptions:
      min: 1
  type: style
...
openapi-v3-operations-tags-one:
  description: Ensures that each of the operations have at least one tag.
  message: All of your operations need to have at least one tag.
  given: $
  severity: error
  then:
    field: tags
    function: length
    functionOptions:
      min: 1
  type: style
