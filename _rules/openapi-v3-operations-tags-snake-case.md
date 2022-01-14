openapi-v3-operations-tags-snake-case:
    description: Ensures that each of the operation tags are snake-case.
    message: Your operation tag "{{value}}" SHOULD be snake-case.
    severity: warn
    formats:
      - oas3
    given: $.paths.*[get,post,patch,put,delete].tags[*]
    recommended: true
    then:
      function: casing
      functionOptions:
        type: snake
    type: style
