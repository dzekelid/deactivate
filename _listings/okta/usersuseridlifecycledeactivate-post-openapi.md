---
swagger: "2.0"
x-collection-name: Okta
x-complete: 0
info:
  title: Okta Deactivate User
  description: Deactivate user.
  version: 1.0.0
host: example.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{userId}/lifecycle/deactivate:
    post:
      summary: Deactivate User
      description: Deactivate user.
      operationId: postUsersUserLifecycleDeactivate
      x-api-path-slug: usersuseridlifecycledeactivate-post
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - User
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---