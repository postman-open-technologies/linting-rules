---
schema-names-length:
  description: Schema names should be no more than 10 characters.
  message: Should be less than 10 characters {{ property }}.
  severity: error
  given: $.components.schemas
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
schema-names-length:
  description: Schema names should be no more than 10 characters.
  message: Should be less than 10 characters {{ property }}.
  severity: error
  given: $.components.schemas
  then:
    field: "@key"
    function: length
    functionOptions: 
      max: 20      
  x-status: validated
  x-tags:
      - Schema
      - Length   