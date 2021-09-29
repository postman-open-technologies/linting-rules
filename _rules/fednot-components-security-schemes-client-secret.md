---
description: The client secret should be an 'apiKey' in a 'header' with the name 'X-Ibm-Client-Secret'
message: '''{{property}}: {{value}}'' does not match the value expected by the gateway.'
given: $.components.securitySchemes[Keys.ClientSecret]
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
    match: ^X-Ibm-Client-Secret$
...description: The client secret should be an 'apiKey' in a 'header' with the name 'X-Ibm-Client-Secret'
message: '''{{property}}: {{value}}'' does not match the value expected by the gateway.'
given: $.components.securitySchemes[Keys.ClientSecret]
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
    match: ^X-Ibm-Client-Secret$