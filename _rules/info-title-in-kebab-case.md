---
info-title-in-kebab-case:
  given: $.info.title
  then:
    function: pattern
    functionOptions:
      match: ^[a-z][a-z0-9\-]*$
  type: style
  recommended: true
  formats:
    - oas2
    - oas3  
  message: Error in the format of the api title
  description: The title of the API must be in kebab case.
  severity: error
  x-tags:
    - Info
    - Title  
...
info-title-in-kebab-case:
  given: $.info.title
  then:
    function: pattern
    functionOptions:
      match: ^[a-z][a-z0-9\-]*$
  type: style
  recommended: true
  formats:
    - oas2
    - oas3  
  message: Error in the format of the api title
  description: Error in the format of the api title must be in kebab-case
  severity: error
  x-tags:
    - Info
    - Title 