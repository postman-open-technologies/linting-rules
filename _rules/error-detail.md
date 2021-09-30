---
severity: error
description: Errors must be problem+JSON and include a "detail" field
given: $..responses.[?(@property.toString().startsWith("4") || @property.toString()
  === "500")]
then:
- field: content
  function: truthy
- field: content.application/problem+json.schema
  function: truthy
- field: content.application/problem+json.schema.properties.detail
  function: truthy
...
severity: error
description: Errors must be problem+JSON and include a "detail" field
given: $..responses.[?(@property.toString().startsWith("4") || @property.toString()
  === "500")]
then:
- field: content
  function: truthy
- field: content.application/problem+json.schema
  function: truthy
- field: content.application/problem+json.schema.properties.detail
  function: truthy