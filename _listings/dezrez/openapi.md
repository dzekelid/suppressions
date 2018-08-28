swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/packsupportedsendmethods/{packid}:
    get:
      summary: Get a list of the supported sending methods for a correspondence (ie
        all of the types required by each document in each envelope)
      description: Get a list of the supported sending methods for a correspondence
        (ie all of the types required by each document in each envelope).
      operationId: DocumentGeneration_PackSupportedSendMethodsBypackid
      x-api-path-slug: apidocumentgenerationpacksupportedsendmethodspackid-get
      parameters:
      - in: path
        name: packid
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Supported
      - Sending
      - Methodsa
      - Correspondence
      - (ie
      - ""
      - Of
      - Types
      - Required
      - By
      - Each
      - Document
      - In
      - Each
      - Envelope)