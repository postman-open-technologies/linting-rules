---
no-numeric-ids:
    description: Please avoid exposing IDs as an integer, UUIDs are preferred.
    severity: error
    given: $.paths..parameters[*].[?(@property === "name" && (@ === "id" || @.match(/(_id|Id)$/)))]^.schema
    then:
        function: schema
        functionOptions:
        schema:
            type: object
            not:
            properties:
                type:
                const: integer
            properties:
            format:
                const: uuid    
...
no-numeric-ids:
    description: Please avoid exposing IDs as an integer, UUIDs are preferred.
    severity: error
    given: $.paths..parameters[*].[?(@property === "name" && (@ === "id" || @.match(/(_id|Id)$/)))]^.schema
    then:
        function: schema
        functionOptions:
        schema:
            type: object
            not:
            properties:
                type:
                const: integer
            properties:
            format:
                const: uuid 
