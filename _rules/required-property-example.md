---
severity: error
given: $..[?(@.type == 'object' && @.required)]
then:
- function: requiredPropertyExample
...
given: $..[?(@.type == 'object' && @.required)]
then:
- function: requiredPropertyExample