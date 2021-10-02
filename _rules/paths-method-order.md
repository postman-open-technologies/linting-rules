---
paths-method-order:
  severity: error
  given: $.paths[?(@.get || @.post || @.patch || @.put || @.delete)]
  then:
    function: operationOrdering
  x-status: draft
  x-tags:
      - Tag      
...
paths-method-order:
  severity: error
  given: $.paths[?(@.get || @.post || @.patch || @.put || @.delete)]
  then:
    function: operationOrdering
  x-status: draft
  x-tags:
      - Tag      