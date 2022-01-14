openapi-v3-operations-tags-camel-case:
    description: Ensures that each of the operation tags are camelCase.
    message: Your operation tag "{{value}}" SHOULD be camelCase.
    severity: warn
    formats:
      - oas3
    given: $.paths.*[get,post,patch,put,delete].tags[*]
    recommended: true
    then:
      function: casing
      functionOptions:
        type: camel
    type: style
