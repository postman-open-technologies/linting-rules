---
name: disallow-uri-versioning-in-paths
object: pathItem
description: paths shouldn't contain version numbers
pattern:
  property: "$key"
  split: "/"
  value: "^((?!v[0-9]).)*$"    
...
name: disallow-uri-versioning-in-paths
object: pathItem
description: paths shouldn't contain version numbers
pattern:
  property: "$key"
  split: "/"
  value: "^((?!v[0-9]).)*$"    