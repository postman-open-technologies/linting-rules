---
severity: error
given: $.paths[?(@.get || @.post || @.patch || @.put || @.delete)]
then:
  function: operationOrdering
...
given: $.paths[?(@.get || @.post || @.patch || @.put || @.delete)]
then:
  function: operationOrdering