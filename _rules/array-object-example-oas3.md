---
array-object-example-oas3:
  severity: error
  message: Did not expect {{property}}at {{path}}. Define example data on each property
    in the object instead
  given: $.paths.*.*.requestBody..[?(@.items)][?(@.type == 'object')]
  formats:
    - oas3  
  then:
  - field: example
    function: falsy
  x-tags:
    - Arrays    
...
array-object-example-oas3:
  severity: error
  message: Did not expect {{property}}at {{path}}. Define example data on each property
    in the object instead
  given: $.paths.*.*.requestBody..[?(@.items)][?(@.type == 'object')]
  formats:
    - oas3  
  then:
  - field: example
    function: falsy
  x-tags:
    - Arrays 