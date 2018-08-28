---
swagger: "2.0"
x-collection-name: Ship Station
x-complete: 0
info:
  title: Ship Station Deactivate Store
  description: |-
    Deactivates the specified store.

    The body of this request has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``storeId``  | number, required | ID of the store to deactivate.
  version: 1.0.0
host: ssapi.shipstation.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /stores/deactivate:
    post:
      summary: Deactivate Store
      description: |-
        Deactivates the specified store.

        The body of this request has the following attributes:

        Name               |Data Type          |Description
        -------------------|-------------------|-------------------
        ``storeId``  | number, required | ID of the store to deactivate.
      operationId: stores.deactivate.post
      x-api-path-slug: storesdeactivate-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Store
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