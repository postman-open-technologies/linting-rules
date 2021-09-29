---
description: The client ID should be an 'apiKey' in a 'header' with the name 'X-Ibm-Client-Id'
message: '''{{property}}: {{value}}'' does not match the value expected by the gateway.'
given: $.components.securitySchemes[Keys.ClientId]
severity: error
then:
- field: type
  function: pattern
  functionOptions:
    match: ^apiKey$
- field: in
  function: pattern
  functionOptions:
    match: ^header$
- field: name
  function: pattern
  functionOptions:
    match: ^X-Ibm-Client-Id$
...
message: '''{{property}}: {{value}}'' does not match the value expected by the gateway.'
given: $.components.securitySchemes[Keys.ClientId]
severity: error
then:
- field: type
  function: pattern
  functionOptions:
    match: ^apiKey$
- field: in
  function: pattern
  functionOptions:
    match: ^header$
- field: name
  function: pattern
  functionOptions:
    match: ^X-Ibm-Client-Id$