---
tags-one:
  description: Must have at least one tag.
  given: $
  severity: error
  then:
    field: tags
    function: length
    functionOptions:
      min: 1
  type: style
  x-status: validated
  x-tags:
      - Tags    
...
tags-one:
  description: Must have at least one tag.
  given: $
  severity: error
  then:
    field: tags
    function: length
    functionOptions:
      min: 1
  type: style
  x-status: validated
  x-tags:
      - Tags    