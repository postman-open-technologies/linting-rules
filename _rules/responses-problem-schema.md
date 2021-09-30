---
responses-problem-schema:
  description: WARN This rule is under implementation and just provides an hint.Error  management is a key enabler of a resilient API ecosystem.Enforcing a consistent schema for errors between different APIs,enables client to properly implement an error management strategy,with positive impacts for users.Errors should return RFC7807 objects. Instead, this schema seems to use non standard properties such a message, msg and code.An error of the following form{  "msg" "Book with id 123 does not exist.",  "code" 6063}can be expressed in RFC7807 with{  "detail" "Book with id 123 does not exist.",  "type" "https//api.example/v1/errors/6063",  "status" 404,  "title" "Not Found"}Returning an URI in type, instead of an opaque code can help the client in better identifying the error; moreover the URIthough it should not be dereferenced automatically, can return an actual resource providing guidance in addressing the issue.See recommendation RAC_REST_NAME_007.
  message: Error response doesnt seem to match RFC7807. Are you sure it is ok? {{path}}
  formats:
  - oas3
  severity: hint
  recommended: true
  given: $.[responses][?(@property.match(/^(4|5|default)/))][[schema]][properties].*~
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: message|code|msg
...
responses-problem-schema:
  description: WARN This rule is under implementation and just provides an hint.Error  management is a key enabler of a resilient API ecosystem.Enforcing a consistent schema for errors between different APIs,enables client to properly implement an error management strategy,with positive impacts for users.Errors should return RFC7807 objects. Instead, this schema seems to use non standard properties such a message, msg and code.An error of the following form{  "msg" "Book with id 123 does not exist.",  "code" 6063}can be expressed in RFC7807 with{  "detail" "Book with id 123 does not exist.",  "type" "https//api.example/v1/errors/6063",  "status" 404,  "title" "Not Found"}Returning an URI in type, instead of an opaque code can help the client in better identifying the error; moreover the URIthough it should not be dereferenced automatically, can return an actual resource providing guidance in addressing the issue.See recommendation RAC_REST_NAME_007.
  message: Error response doesnt seem to match RFC7807. Are you sure it is ok? {{path}}
  formats:
  - oas3
  severity: hint
  recommended: true
  given: $.[responses][?(@property.match(/^(4|5|default)/))][[schema]][properties].*~
  then:
    field: '@key'
    function: pattern
    functionOptions:
      notMatch: message|code|msg