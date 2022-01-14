openapi-v3-operations-tags-kebab-case:
    description: Ensures that each of the operation tags are kebab-case.
    message: Your operation tag "{{value}}" SHOULD be kebab-case.
    severity: warn
    formats:
      - oas3
    given: $.paths.*[get,post,patch,put,delete].tags[*]
    recommended: true
    then:
      function: casing
      functionOptions:
        type: kebab
    type: style
