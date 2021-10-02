--- 
operations-summary-words-check: 
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Words  
...
operations-summary-words-check: 
  description: "Must not contain specific words, including REST, Public, and Developer."
  given: $.paths.*[get,post,patch,put,delete]
  recommended: true
  then:
    function: pattern
    functionOptions:
      notMatch: \b(word|word|word)\b
  type: style
  x-status: validated
  x-tags:
    - Operations
    - Words 