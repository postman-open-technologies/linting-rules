---
has-info-title:
    description: API must have a info title.
    message: "Missing the {{property}}"
    given: "$"
    then:
        - field: "description"
          function: truthy  
...
has-info-title:
    description: API must have a info title.
    message: "Missing the {{property}}"
    given: "$"
    then:
    - field: "description"
        function: truthy  