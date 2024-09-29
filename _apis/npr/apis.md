name: NPR
description: >-
  National Public Radio (NPR) APIs. The APIs support station finding,
  authentication, user management and listening.
url: https://raw.githubusercontent.com/api-search/news/main/_apis/npr/apis.md
created: 2024/04/14
modified: '2024-07-03'
specificationVersion: '0.18'
tags: []
apis:
  - name: Listening
    description: Audio recommendations tailored to a user's preferences.
    tags: []
    contact:
      - FN: ''
        url: ''
        email: ''
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://listening.api.npr.org/v2/swagger.json-openapi-search.yml
    aid: npr:listening
  - name: Station
    description: NPR Station information.
    tags: []
    contact:
      - FN: ''
        url: ''
        email: ''
    overlays: []
    aid: npr:station
  - name: Identity
    description: User management API.
    tags: []
    contact:
      - FN: ''
        url: ''
        email: ''
    overlays: []
    aid: npr:identity
  - name: Authorization
    description: API Authorization.
    tags: []
    contact:
      - FN: ''
        url: ''
        email: ''
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://authorization.api.npr.org/v2/swagger.json-openapi-search.yml
    aid: npr:authorization
maintainers:
  - FN: Steven Willmott
    url: http://timewarp.com
    email: steve@timewarp.io
aid: npr
