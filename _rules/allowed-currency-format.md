---
allowed-currency-format:
  description: currency must fit the ISO standard
  message: '{{error}}'
  recommended: true
  type: style
  given: $.[?(/~*/.test(@.currency))].*.currency
  severity: error
  resolved: false
  then:
    function: checkCurrency
  x-status: draft
  x-tags:
    - Currency
    - Formats
...
allowed-currency-format:
  description: currency must fit the ISO standard
  message: '{{error}}'
  recommended: true
  type: style
  given: $.[?(/~*/.test(@.currency))].*.currency
  severity: error
  resolved: false
  then:
    function: checkCurrency
  x-status: draft
  x-tags:
    - Currency
    - Formats    