---
name: NPR
description: >-
  National Public Radio (NPR) APIs. The APIs support station finding,
  authentication, user management and listening.
image: https://dev.npr.org/NPRLogo_BlackOutline.png
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/npr.yml
created: 2023-11-11
modified: 2024-06-14
specificationVersion: '0.16'
tags: []
apis:
  - name: Station
    description: NPR Station information.
    image: https://dev.npr.org/NPRLogo_BlackOutline.png
    humanURL: https://dev.npr.org/?urls.primaryName=station
    baseURL: https://station.api.npr.org
    tags: []
    properties:
      - type: Documentation
        url: https://dev.npr.org/?urls.primaryName=station
      - type: OpenAPI
        url: properties/npr-station-finder-openapi-original.yml
    aid: npr:station
  - name: Identity
    description: User management API.
    image: https://dev.npr.org/NPRLogo_BlackOutline.png
    humanURL: https://dev.npr.org/?urls.primaryName=identity
    baseURL: https://identity.api.npr.org
    tags: []
    properties:
      - type: Documentation
        url: https://dev.npr.org/?urls.primaryName=identity
      - type: Swagger
        url: properties/npr-identity-openapi-original.yml
    aid: npr:identity
  - name: Authorization
    description: API Authorization.
    image: https://dev.npr.org/NPRLogo_BlackOutline.png
    humanURL: https://dev.npr.org/?urls.primaryName=authorization
    baseURL: https://authorization.api.npr.org
    tags: []
    properties:
      - type: Documentation
        url: https://dev.npr.org/?urls.primaryName=authorization
      - type: OpenAPI
        url: properties/npr-authorization-openapi-original.yml
    aid: npr:authorization
maintainers:
  - FN: Steven Willmott
    url: http://timewarp.com
    email: steve@timewarp.io
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
aid: npr
---