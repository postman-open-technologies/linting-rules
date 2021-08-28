---
name: path-segments-lowercased-hyphens
object: paths
description: path items must be lowercase and separated with hyphens
pattern:
  property: "$key"
  split: "/"
  value: "^{[^}]*}$|^([a-z-\/]*)$"     
...
name: path-segments-lowercased-hyphens
object: paths
description: path items must be lowercase and separated with hyphens
pattern:
  property: "$key"
  split: "/"
  value: "^{[^}]*}$|^([a-z-\/]*)$"   
