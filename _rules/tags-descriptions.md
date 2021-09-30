---
tags-description:
    description: "Tags must have a description."
    given: $.tags[*]
    severity: error
    then:
        field: description
        function: truthy    
...
tags-description:
    description: "Tags must have a description."
    given: $.tags[*]
    severity: error
    then:
        field: description
        function: truthy   