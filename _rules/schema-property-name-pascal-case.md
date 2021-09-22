---
name: schema-property-name-pascal-case
object: schema
disabled: false,
description: "schema property must be in PascalCase "
pattern:
  property: "$key"
  omit: "properties/"
  value: "^[A-Z][a-z-](?:[A-Z][a-z-]*)*$"        
...
name: schema-property-name-pascal-case
object: schema
disabled: false,
description: "schema property must be in PascalCase"
pattern:
  property: "$key"
  omit: "properties/"
  value: "^[A-Z][a-z-](?:[A-Z][a-z-]*)*$"   


value: ^[A-Z][a-zA-Z]*$