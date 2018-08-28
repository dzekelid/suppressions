---
swagger: "2.0"
x-collection-name: Azure Storage
x-complete: 0
info:
  title: Azure Storage API List Supported Operations
  version: 1.0.0
  description: Returns the list of operations supported by the import/export resource
    provider.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/Microsoft.ImportExport/operations:
    get:
      summary: List Supported Operations
      description: Returns the list of operations supported by the import/export resource
        provider.
      operationId: ListSupportedOperations
      x-api-path-slug: providersmicrosoft-importexportoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Supported Operations
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