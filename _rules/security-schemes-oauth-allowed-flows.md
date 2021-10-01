---
security-schemes-oauth-allowed-flows:
    description: >-
        The OAuth2 authorization framework defines various [grant types](https://tools.ietf.org/html/rfc6749#section-1.3), most notably the [AuthorizationCode](https://tools.ietf.org/html/rfc6749#section-1.3.1) and the [Client Credentials](https://tools.ietf.org/html/rfc6749#section-1.3.4). Some grant types are now considered insecure and MUST not be used, including `implicit` and `password`. The new [OAuth2.1](https://tools.ietf.org/html/draft-ietf-oauth-v2-1-01)  still in draft, removes them and suggests to replace the `implicit` with `authorizationCode` + PKCE defined in RFC7636.
    message: 'Do not use oauth2 insecure flow: "{{property}}".'
    formats:
        - oas3
    severity: error
    recommended: true
    given:
        - $.[?(@.type=="oauth2")].flows
    then:
        - field: implicit
          function: falsy
        - field: password
          function: falsy
...
security-schemes-oauth-allowed-flows:
    description: >-
        The OAuth2 authorization framework defines various [grant types](https://tools.ietf.org/html/rfc6749#section-1.3), most notably the [AuthorizationCode](https://tools.ietf.org/html/rfc6749#section-1.3.1) and the [Client Credentials](https://tools.ietf.org/html/rfc6749#section-1.3.4). Some grant types are now considered insecure and MUST not be used, including `implicit` and `password`. The new [OAuth2.1](https://tools.ietf.org/html/draft-ietf-oauth-v2-1-01)  still in draft, removes them and suggests to replace the `implicit` with `authorizationCode` + PKCE defined in RFC7636.
    message: 'Do not use oauth2 insecure flow: "{{property}}".'
    formats:
        - oas3
    severity: error
    recommended: true
    given:
        - $.[?(@.type=="oauth2")].flows
    then:
        - field: implicit
          function: falsy
        - field: password
          function: falsy