---
swagger: "2.0"
x-collection-name: Akeneo
x-complete: 1
info:
  title: Official Akeneo PIM API
  description: the-akeneo-api-brought-to-youfind-out-how-this-postman-collection-works-by-visiting-httpapi-akeneo-com
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
  /rest/v1/product-models/amor/proposal:
    post:
      summary: proposal (2.3 and EE only)
      description: |-
        Assuming that there is already a draft for the given product model. The draft was created by the same user using this request.
        The user has only an edition permission through categories on the given product model.
      operationId: RestV1ProductModelsAmorProposalPost
      x-api-path-slug: restv1productmodelsamorproposal-post
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
      - "3"
      - EE
      - Only)
---