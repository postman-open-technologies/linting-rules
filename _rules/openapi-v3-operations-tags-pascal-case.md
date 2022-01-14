---
openapi-v3-operations-tags-pascal-case:
    description: Ensures that each of the operation tags are PascalCase.
    message: Your operation tag "{{value}}" SHOULD be PascalCase.
    severity: warn
    formats:
      - oas3
    given: $.paths.*[get,post,patch,put,delete].tags[*]
    recommended: true
    then:
      function: casing
      functionOptions:
        type: pascal
    type: style
...
openapi-v3-operations-tags-pascal-case:
    description: Ensures that each of the operation tags are PascalCase.
    message: Your operation tag "{{value}}" SHOULD be PascalCase.
    severity: warn
    formats:
      - oas3
    given: $.paths.*[get,post,patch,put,delete].tags[*]
    recommended: true
    then:
      function: casing
      functionOptions:
        type: pascal
    type: style
