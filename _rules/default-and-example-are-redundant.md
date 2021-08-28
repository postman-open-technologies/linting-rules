---
name: default-and-example-are-redundant
object: "*"
description: don't need to define an example if its exactly the same as your default
schema:
  dependencies:
    default:
      properties:
        example:
          not:
            const:
              "$data": "1/default"      
...
name: default-and-example-are-redundant
object: "*"
description: don't need to define an example if its exactly the same as your default
schema:
  dependencies:
    default:
      properties:
        example:
          not:
            const:
              "$data": "1/default"     