swagger: "2.0"
x-collection-name: Dyn
x-complete: 1
info:
  title: Dyn
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  suppressions:
    get:
      summary: Retrieve Suppression Email Addresses
      description: Retrieving a list of Email addresses on the suppression list
      operationId: getSuppressions
      x-api-path-slug: suppressions-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: startdate
        description: Start date/time range in full, ISO 8601 format
      - in: query
        name: startindex
        description: Starting index value
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Suppression
      - Email
      - resses
    post:
      summary: Add Email Address to Suppression List
      description: Adding one or more recipients to the suppression list
      operationId: postSuppressions
      x-api-path-slug: suppressions-post
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: emailaddress
        description: Required
      responses:
        200:
          description: OK
      tags:
      - .Email
      - ress
      - to
      - Suppression
      - List
  suppressions/count:
    get:
      summary: Retrieve Suppression Count
      description: Retrieving the count of Email addresses on the suppression list
      operationId: getSuppressionsCount
      x-api-path-slug: suppressionscount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: enddate
        description: End date/time range in full, ISO 8601 format
      - in: query
        name: startdate
        description: Start date/time range in full, ISO 8601 format
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Suppression
      - Count