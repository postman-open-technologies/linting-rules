---
name: Responses
description: A ruleset that focus on governance applied to the responses object of the OpenAPI.
rules:
    - response-get-200-status-code
    - response-get-200-media-type
    - response-get-200-no-body
    - response-get-500-status-code
    - response-get-500-media-type
    - response-post-201-status-code
    - response-post-201-media-type
    - response-post-500-status-code
    - response-post-500-media-type
    - response-put-204-status-code
    - response-put-204-no-body
    - response-put-500-status-code
    - response-put-500-media-type
    - response-delete-204-status-code
    - response-delete-204-no-body
    - response-delete-500-status-code
    - response-delete-500-media-type
image: /images/responses-icon.png
tags:
  - OpenAPI
discussion: https://github.com/postman-open-technologies/linting-rules/discussions/18
...