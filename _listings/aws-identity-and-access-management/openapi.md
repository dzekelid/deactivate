swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 1
info:
  title: AWS Identity and Access Management API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeactivateMFADevice:
    get:
      summary: Deactivate M F A Device
      description: |-
        Deactivates the specified MFA device and removes it from association with the user name
              for which it was originally enabled.
      operationId: deactivateMFADevice
      x-api-path-slug: actiondeactivatemfadevice-get
      parameters:
      - in: query
        name: SerialNumber
        description: The serial number that uniquely identifies the MFA device
        type: string
      - in: query
        name: UserName
        description: The name of the user whose MFA device you want to deactivate
        type: string
      responses:
        200:
          description: OK
      tags:
      - Virtual MFA Device