--- 
string-maxlength: 
  description: |-
      String length should be limited to avoid an attacker to send very long strings to your service.
  formats: 
    - oas3
  given: 
    - "$.[?(@.type==\"string\" && !@.enum && @.format!=\"date\" && @.format!=\"date-time\" )]"
  message: "Strings (non enum) must specify a maximum length. {{path}} {{error}}"
  recommended: true
  severity: warn
  then: 
    - 
      field: maxLength
      function: defined
...
string-maxlength: 
  description: |-
      String length should be limited to avoid an attacker to send very long strings to your service.
  formats: 
    - oas3
  given: 
    - "$.[?(@.type==\"string\" && !@.enum && @.format!=\"date\" && @.format!=\"date-time\" )]"
  message: "Strings (non enum) must specify a maximum length. {{path}} {{error}}"
  recommended: true
  severity: warn
  then: 
    - 
      field: maxLength
      function: defined
