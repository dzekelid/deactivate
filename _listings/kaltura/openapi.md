---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 1
info:
  title: Kaltura VPaaS
  description: building-video-experiences-consists-of-ingesting-media-files-playing-back-videos-and-reviewing-usage-and-engagement-analytics--in-between-there-is-a-world-of-nuances-required-for-your-unique-usecase-and-application--kaltura-vpaas-is-built-on-the-principles-of-atomic-services-sdks-and-tools-that-allow-you-full-control-and-flexibility-over-every-element-and-process-in-your-medias-life-cycle-
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/categoryuser/action/deactivate:
    get:
      summary: Get Service Categoryuser Action Deactivate
      description: reject CategoryUser
      operationId: categoryUser.deactivate
      x-api-path-slug: servicecategoryuseractiondeactivate-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: No Name
      - in: query
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - Deactivate
---