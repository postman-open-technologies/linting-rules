---
protocol-https-only-oas3:
  description: "ALL requests MUST go through `https` protocol only"
  formats: 
    - oas3
  given: $.servers..url
  message: "Servers MUST be https and no other protocol is allowed."
  severity: error
  then: 
    function: pattern
    functionOptions: ~
    match: "/^https:/"
...
protocol-https-only-oas3:
  description: "ALL requests MUST go through `https` protocol only"
  formats: 
    - oas3
  given: $.servers..url
  message: "Servers MUST be https and no other protocol is allowed."
  severity: error
  then: 
    function: pattern
    functionOptions: ~
    match: "/^https:/"