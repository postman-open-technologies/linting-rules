---
has-tag-description:
    description: "Tags must have a description."
    given: $.tags[*]
    severity: error
    then:
        field: description
        function: truthy    
...
has-tag-description:
    description: "Tags must have a description."
    given: $.tags[*]
    severity: error
    then:
        field: description
        function: truthy 