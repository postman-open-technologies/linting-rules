---
description: FedNot uses a standardised error model
message: '{{error}}. You can find the error model to use on Integration Team''s Confluence
  at pageId=77477195.'
given: $.components.responses.Error.content.application/json
severity: error
then:
  field: schema
  function: schema
  functionOptions:
    schema:
      type: object
      required:
      - type
      - description
      - required
      - properties
      properties:
        type:
          type: string
          enum:
          - object
        description:
          type: string
        required:
          type: array
          items:
            type: string
            enum:
            - timestamp
            - title
            - instance
            - type
            - status
            - detail
          minItems: 6
        properties:
          type: object
          required:
          - timestamp
          - title
          - instance
          - type
          - status
          - detail
          - errors
          properties:
            timestamp:
              type: object
              required:
              - type
              - format
              properties:
                type:
                  type: string
                  enum:
                  - string
                format:
                  type: string
                  enum:
                  - date-time
            title:
              type: object
              required:
              - type
              properties:
                type:
                  type: string
                  enum:
                  - string
            instance:
              type: object
              required:
              - type
              properties:
                type:
                  type: string
                  enum:
                  - string
            type:
              type: object
              required:
              - type
              properties:
                type:
                  type: string
                  enum:
                  - string
            status:
              type: object
              required:
              - type
              - format
              properties:
                type:
                  type: string
                  enum:
                  - integer
                format:
                  type: string
                  enum:
                  - int32
            detail:
              type: object
              required:
              - type
              properties:
                type:
                  type: string
                  enum:
                  - string
            errors:
              type: object
              required:
              - type
              - items
              properties:
                type:
                  type: string
                  enum:
                  - array
                items:
                  type: object
                  required:
                  - type
                  - properties
                  properties:
                    type:
                      type: string
                      enum:
                      - object
                    properties:
                      type: object
                      required:
                      - resource
                      - field
                      - detail
                      - code
                      properties:
                        resource:
                          type: object
                          required:
                          - type
                          properties:
                            type:
                              type: string
                              enum:
                              - string
                        detail:
                          type: object
                          required:
                          - type
                          properties:
                            type:
                              type: string
                              enum:
                              - string
                        field:
                          type: object
                          required:
                          - type
                          properties:
                            type:
                              type: string
                              enum:
                              - string
                        code:
                          type: object
                          required:
                          - type
                          properties:
                            type:
                              type: string
                              enum:
                              - string
...description: FedNot uses a standardised error model
message: '{{error}}. You can find the error model to use on Integration Team''s Confluence
  at pageId=77477195.'
given: $.components.responses.Error.content.application/json
severity: error
then:
  field: schema
  function: schema
  functionOptions:
    schema:
      type: object
      required:
      - type
      - description
      - required
      - properties
      properties:
        type:
          type: string
          enum:
          - object
        description:
          type: string
        required:
          type: array
          items:
            type: string
            enum:
            - timestamp
            - title
            - instance
            - type
            - status
            - detail
          minItems: 6
        properties:
          type: object
          required:
          - timestamp
          - title
          - instance
          - type
          - status
          - detail
          - errors
          properties:
            timestamp:
              type: object
              required:
              - type
              - format
              properties:
                type:
                  type: string
                  enum:
                  - string
                format:
                  type: string
                  enum:
                  - date-time
            title:
              type: object
              required:
              - type
              properties:
                type:
                  type: string
                  enum:
                  - string
            instance:
              type: object
              required:
              - type
              properties:
                type:
                  type: string
                  enum:
                  - string
            type:
              type: object
              required:
              - type
              properties:
                type:
                  type: string
                  enum:
                  - string
            status:
              type: object
              required:
              - type
              - format
              properties:
                type:
                  type: string
                  enum:
                  - integer
                format:
                  type: string
                  enum:
                  - int32
            detail:
              type: object
              required:
              - type
              properties:
                type:
                  type: string
                  enum:
                  - string
            errors:
              type: object
              required:
              - type
              - items
              properties:
                type:
                  type: string
                  enum:
                  - array
                items:
                  type: object
                  required:
                  - type
                  - properties
                  properties:
                    type:
                      type: string
                      enum:
                      - object
                    properties:
                      type: object
                      required:
                      - resource
                      - field
                      - detail
                      - code
                      properties:
                        resource:
                          type: object
                          required:
                          - type
                          properties:
                            type:
                              type: string
                              enum:
                              - string
                        detail:
                          type: object
                          required:
                          - type
                          properties:
                            type:
                              type: string
                              enum:
                              - string
                        field:
                          type: object
                          required:
                          - type
                          properties:
                            type:
                              type: string
                              enum:
                              - string
                        code:
                          type: object
                          required:
                          - type
                          properties:
                            type:
                              type: string
                              enum:
                              - string