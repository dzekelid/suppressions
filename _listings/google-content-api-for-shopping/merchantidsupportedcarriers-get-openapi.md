---
swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 0
info:
  title: Google Content API for Shopping API Get Supported Carriers
  description: Retrieves supported carriers and carrier services for an account.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /content/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{merchantId}/supportedCarriers:
    get:
      summary: Get Supported Carriers
      description: Retrieves supported carriers and carrier services for an account.
      operationId: content.shippingsettings.getsupportedcarriers
      x-api-path-slug: merchantidsupportedcarriers-get
      parameters:
      - in: path
        name: merchantId
        description: The ID of the account for which to retrieve the supported carriers
      responses:
        200:
          description: OK
      tags:
      - Supported
      - Carriers
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