---
description: FedNot's error model should be defined in the responses
given: $.components.responses
severity: error
then:
  field: Error
  function: truthy
...
given: $.components.responses
severity: error
then:
  field: Error
  function: truthy