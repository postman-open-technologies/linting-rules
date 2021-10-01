---
definitions-properties-maxlength:
  description: Las propiedades de tipo cadena deben contener la propiedad maxLength
    (máxima longitud de cadena).
  given:
  - $.definitions.*.properties.[?(@.type=="string")]
  - $.definitions.*.properties.[?(@.type=="string")]
  message: SWAG09 String-type properties MUST contain maxLength property (maximum
    length of string).
  recommended: true
  severity: info
  then:
    field: maxLength
    function: truthy
  x-status: draft
  x-tags:
    - Tag    
...
definitions-properties-maxlength:
  description: Las propiedades de tipo cadena deben contener la propiedad maxLength
    (máxima longitud de cadena).
  given:
  - $.definitions.*.properties.[?(@.type=="string")]
  - $.definitions.*.properties.[?(@.type=="string")]
  message: SWAG09 String-type properties MUST contain maxLength property (maximum
    length of string).
  recommended: true
  severity: info
  then:
    field: maxLength
    function: truthy
  x-status: draft
  x-tags:
    - Tag    