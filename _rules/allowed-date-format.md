---
allowed-date-format:
  description: String properties with the date format must end in Date.
  given: $..properties.[?(@.format=="date" && @.type=="string")]~
  then:
    function: pattern
    functionOptions:
      match: ((d)|(.D))ate$
...
allowed-date-format:
  description: String properties with the date format must end in Date.
  given: $..properties.[?(@.format=="date" && @.type=="string")]~
  then:
    function: pattern
    functionOptions:
      match: ((d)|(.D))ate$