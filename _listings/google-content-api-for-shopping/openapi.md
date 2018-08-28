swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 1
info:
  title: Content API for Shopping
  description: manages-product-items-inventory-and-merchant-center-accounts-for-google-shopping-
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