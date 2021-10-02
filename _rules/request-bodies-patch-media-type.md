--- 
request-bodies-patch-media-type: 
  description: "The PATCH specification explicits that the request body contains a \"patch document\" describing the changes to be applied to the target resource. To avoid confusion, [this errata](https://www.rfc-editor.org/errata/eid3169) explains that `application/json` is not an appropriate media-type for `PATCH`. A correct example of PATCH using eg. `application/json-patch+json` media-type defined in RFC6902."
  formats: 
    - oas3
  given: "$.[patch][requestBody][content]"
  message: "application/json is not an appropriate media-type for PATCH. {{path}}"
  recommended: true
  severity: error
  then: 
    field: application/json
    function: falsy
  x-status: draft
  x-tags:
    - Tag  
...
request-bodies-patch-media-type: 
  description: "The PATCH specification explicits that the request body contains a \"patch document\" describing the changes to be applied to the target resource. To avoid confusion, [this errata](https://www.rfc-editor.org/errata/eid3169) explains that `application/json` is not an appropriate media-type for `PATCH`. A correct example of PATCH using eg. `application/json-patch+json` media-type defined in RFC6902."
  formats: 
    - oas3
  given: "$.[patch][requestBody][content]"
  message: "application/json is not an appropriate media-type for PATCH. {{path}}"
  recommended: true
  severity: error
  then: 
    field: application/json
    function: falsy
  x-status: draft
  x-tags:
    - Tag  
