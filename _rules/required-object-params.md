---
severity: error
given: $.paths.*.[post].requestBody.content.*.[?(@.required)]
then:
  function: objectRequiredProperties
...
given: $.paths.*.[post].requestBody.content.*.[?(@.required)]
then:
  function: objectRequiredProperties