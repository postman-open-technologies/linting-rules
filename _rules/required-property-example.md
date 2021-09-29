---
severity: error
given: $..[?(@.type == 'object' && @.required)]
then:
- function: requiredPropertyExample
...severity: error
given: $..[?(@.type == 'object' && @.required)]
then:
- function: requiredPropertyExample