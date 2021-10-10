---
schema-properties-names-length:
  description: Schema property names should be no more than 10 characters.
  message: Should be less than 10 characters {{ property }}.
  severity: error
  given: $..properties.*
  then:
    field: "@key"
    function: length
    functionOptions: 
      max: 20      
  x-status: validated
  x-tags:
      - Schema
      - Length          
...
schema-properties-names-length:
  description: Schema property names should be no more than 10 characters.
  message: Should be less than 10 characters {{ property }}.
  severity: error
  given: $..properties.*
  then:
    field: "@key"
    function: length
    functionOptions: 
      max: 20      
  x-status: validated
  x-tags:
      - Schema
      - Length   