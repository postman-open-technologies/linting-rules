---
description: |-
  String length should be limited to avoid an attacker
  to send very long strings to your service.For further security, you can always limit string length even
  in conjunction with `format` and `pattern`.
message: Strings (non enum) must specify a maximum length. {{path}} {{error}}
formats:
- oas3
severity: warn
recommended: true
given:
- $.[?(@.type=="string" && !@.enum && @.format!="date" && @.format !="date-time" )]
then:
- field: maxLength
  function: defined
...
description: |-
  String length should be limited to avoid an attacker
  to send very long strings to your service.For further security, you can always limit string length even
  in conjunction with `format` and `pattern`.
message: Strings (non enum) must specify a maximum length. {{path}} {{error}}
formats:
- oas3
severity: warn
recommended: true
given:
- $.[?(@.type=="string" && !@.enum && @.format!="date" && @.format !="date-time" )]
then:
- field: maxLength
  function: defined