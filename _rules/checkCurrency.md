---
description: currency must fit the ISO standard
message: '{{error}}'
recommended: true
type: style
given: $.[?(/~*/.test(@.currency))].*.currency
severity: error
resolved: false
then:
  function: checkCurrency
...
message: '{{error}}'
recommended: true
type: style
given: $.[?(/~*/.test(@.currency))].*.currency
severity: error
resolved: false
then:
  function: checkCurrency