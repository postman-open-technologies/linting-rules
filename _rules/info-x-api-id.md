---
info-x-api-id:
    x-tags:
        - it
        - metadata
    message: "API must have an unique identifier in x-api-id in #/info/x-api-id."
    description: |-
        The `#/info/x-api-id` field can be used to associate an identifier
        to an API. This is useful to track an API even when its `#/info/title` changes.
    given: "$.info"
    severity: error
    recommended: true
    type: style
    then:
        field: x-api-id
        function: truthy
...
info-x-api-id:
    x-tags:
        - it
        - metadata
    message: "API must have an unique identifier in x-api-id in #/info/x-api-id."
    description: |-
        The `#/info/x-api-id` field can be used to associate an identifier
        to an API. This is useful to track an API even when its `#/info/title` changes.
    given: "$.info"
    severity: error
    recommended: true
    type: style
    then:
        field: x-api-id
        function: truthy