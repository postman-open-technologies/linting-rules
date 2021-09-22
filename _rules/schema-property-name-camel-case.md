---
name: schema-property-name-camel-case
object: schema
disabled: false,
description: "schema property must be in camelCase "
pattern:
  property: "$key"
  omit: "properties/"
  value: ^[A-Z][a-zA-Z]*$       
...
name: schema-property-name-camel-case
object: schema
disabled: false,
description: "schema property must be in camelCase"
pattern:
  property: "$key"
  omit: "properties/"
  value: ^[A-Z][a-zA-Z]*$