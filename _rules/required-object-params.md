---
severity: error
given: $.paths.*.[post].requestBody.content.*.[?(@.required)]
then:
  function: objectRequiredProperties
...severity: error
given: $.paths.*.[post].requestBody.content.*.[?(@.required)]
then:
  function: objectRequiredProperties