---
tags-description:
    description: "Tags must have a description."
    given: $.tags[*]
    severity: error
    then:
        field: description
        function: truthy  
    x-status: validated
    x-tags:
        - Tag           
...
tags-description:
    description: "Tags must have a description."
    given: $.tags[*]
    severity: error
    then:
        field: description
        function: truthy  
    x-status: validated
    x-tags:
        - Tag          