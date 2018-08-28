---
swagger: "2.0"
x-collection-name: Akeneo
x-complete: 0
info:
  title: Akeneo PIM API proposal (2.x and EE only)
  description: |-
    Assuming that there is already a draft for the given product. The draft was created by the same user using this request.
    The user has only an edition permission through categories on the given product.
  version: 1.0.0
host: example.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/v1/products/AKNTS_BPS/proposal:
    post:
      summary: proposal (2.x and EE only)
      description: |-
        Assuming that there is already a draft for the given product. The draft was created by the same user using this request.
        The user has only an edition permission through categories on the given product.
      operationId: RestV1ProductsAKNTSBPSProposalPost
      x-api-path-slug: restv1productsaknts-bpsproposal-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Proposal
      - (2
      - X
      - EE
      - Only)
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