---
swagger: "2.0"
x-collection-name: AWS Data Pipeline
x-complete: 1
info:
  title: AWS Data Pipeline API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeactivatePipeline:
    get:
      summary: Deactivate Pipeline
      description: Deactivates the specified running pipeline.
      operationId: deactivatePipeline
      x-api-path-slug: actiondeactivatepipeline-get
      parameters:
      - in: query
        name: cancelActive
        description: Indicates whether to cancel any running objects
        type: string
      - in: query
        name: pipelineId
        description: The ID of the pipeline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
---