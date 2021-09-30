---
severity: error
message: '{{description}}: {{error}}'
given: $..responses.[?(@property == '200' || @ == '201' || @ == '202' || @ == '400' || @ == '401' || @ == '403' || @ == '404' || @ == '422' || @ == '500')].content
then:
  function: contains
  functionOptions:
    match: json
...
severity: error
message: '{{description}}: {{error}}'
given: $..responses.[?(@property == '200' || @ == '201' || @ == '202' || @ == '400' || @ == '401' || @ == '403' || @ == '404' || @ == '422' || @ == '500')].content
then:
  function: contains
  functionOptions:
    match: json