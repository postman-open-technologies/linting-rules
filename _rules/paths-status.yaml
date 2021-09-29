---
x-tags:
- it
description: |-
  You must define a `/status` path that can be used to health-check the API.
  Using this path avoids the arbitrary usage of a server URL for health-check
  scope.

  The `/status` endpoint should return a `application/problem+json` response
  containing a successful status code if the service is working correctly.

  The service provider is free to define the implementation logic for this path.
message: The "/status" path used to health-check the API must be defined. {{error}}
severity: error
recommended: true
given: $
then:
  field: paths./status.get.responses.200
  function: truthy
...x-tags:
- it
description: |-
  You must define a `/status` path that can be used to health-check the API.
  Using this path avoids the arbitrary usage of a server URL for health-check
  scope.

  The `/status` endpoint should return a `application/problem+json` response
  containing a successful status code if the service is working correctly.

  The service provider is free to define the implementation logic for this path.
message: The "/status" path used to health-check the API must be defined. {{error}}
severity: error
recommended: true
given: $
then:
  field: paths./status.get.responses.200
  function: truthy