---
severity: error
given: $.paths[?(@.get || @.post || @.patch || @.put || @.delete)]
then:
  function: operationOrdering
...severity: error
given: $.paths[?(@.get || @.post || @.patch || @.put || @.delete)]
then:
  function: operationOrdering