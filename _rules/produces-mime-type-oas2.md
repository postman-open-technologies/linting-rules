---
produces-mime-type-oas2:
  description: FHIR mime-type must be application/fhir+(xml|json|turtle) or application/x-www-form-urlencoded for search endpoints
  severity: error
  recommended: true
  format: oas2
  given: $..consumes.*
  then:
    function: schema
    functionOptions:
      schema:
        type: string
        enum:
        - application/fhir+xml
        - application/fhir+json
        - application/fhir+turtle
...
produces-mime-type-oas2:
  description: FHIR mime-type must be application/fhir+(xml|json|turtle) or application/x-www-form-urlencoded for search endpoints
  severity: error
  recommended: true
  format: oas2
  given: $..consumes.*
  then:
    function: schema
    functionOptions:
      schema:
        type: string
        enum:
        - application/fhir+xml
        - application/fhir+json
        - application/fhir+turtle