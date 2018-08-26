---
swagger: "2.0"
x-collection-name: AWS WorkDocs
x-complete: 1
info:
  title: AWS WorkDocs API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeactivateUser:
    get:
      summary: Deactivate User
      description: Deactivates the specified user, which revokes the user's access
        to Amazon WorkDocs.
      operationId: deactivateUser
      x-api-path-slug: actiondeactivateuser-get
      parameters:
      - in: query
        name: UserId
        description: The ID of the user
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
---