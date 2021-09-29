---
description: String properties with the `date-time` format must end in `DateTime`.
given: $..properties.[?(@.format=="date-time" && @.type=="string")]~
then:
  function: pattern
  functionOptions:
    match: ((d)|(.D))ateTime$
...description: String properties with the `date-time` format must end in `DateTime`.
given: $..properties.[?(@.format=="date-time" && @.type=="string")]~
then:
  function: pattern
  functionOptions:
    match: ((d)|(.D))ateTime$