---
no-forbidden-headers:
  x-tags:
    - standards
  description: |-
    OAS do not allow using the following HTTP headers in a specification
    file: Authorization, Content-Type and Accept.
    You MUST use the associate functionalities provided by OAS, instead.
  message: "{{error}} in {{path}} {{value}}"
  severity: error
  given:
    - $..parameters[?(@.in == 'header')].name
    - $.[responses][*].headers.*~
  then:
    function: pattern
    functionOptions:
      notMatch: /^(accept|content-type|authorization)$/i      
  x-status: draft
  x-tags:
      - Tag       
...
no-forbidden-headers:
  x-tags:
    - standards
  description: |-
    OAS do not allow using the following HTTP headers in a specification
    file: Authorization, Content-Type and Accept.
    You MUST use the associate functionalities provided by OAS, instead.
  message: "{{error}} in {{path}} {{value}}"
  severity: error
  given:
    - $..parameters[?(@.in == 'header')].name
    - $.[responses][*].headers.*~
  then:
    function: pattern
    functionOptions:
      notMatch: /^(accept|content-type|authorization)$/i   
  x-status: draft
  x-tags:
      - Tag       