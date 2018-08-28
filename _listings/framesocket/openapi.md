swagger: "2.0"
x-collection-name: Framesocket
x-complete: 1
info:
  title: Framesocket
  description: framesocket-is-the-best-way-for-developers-and-content-owners-to-tackle-video-projects-of-any-size-
  version: 1.0.0
host: www.framesocket.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /media/deactivate.php:
    get:
      summary: Deactive Media
      description: Deactive Media
      operationId: getMediaDeactivate.php
      x-api-path-slug: mediadeactivate-php-get
      parameters:
      - in: query
        name: customid
        description: Custom ID
      - in: query
        name: hash
        description: Video Hash
      - in: query
        name: key
        description: Your account username
      - in: query
        name: secret
        description: Your account API secret
      - in: query
        name: sig
        description: This is an md5 hash of your gatekeeper concatenated with your
          request action
      responses:
        200:
          description: OK
      tags:
      - Media
      - Deactivate