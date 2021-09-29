---
severity: error
message: Did not expect {{property}}at {{path}}. Define 'example' data on each property
  in the object instead
given: $.paths.*.*.requestBody..[?(@.items)][?(@.type == 'object')]
then:
- field: example
  function: falsy
...severity: error
message: Did not expect {{property}}at {{path}}. Define 'example' data on each property
  in the object instead
given: $.paths.*.*.requestBody..[?(@.items)][?(@.type == 'object')]
then:
- field: example
  function: falsy