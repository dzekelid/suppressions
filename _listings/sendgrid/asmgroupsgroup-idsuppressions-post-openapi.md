---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Add Asm Groups Group  Suppressions
  description: |-
    **This endpoint allows you to add email addresses to an unsubscribe group.**

    If you attempt to add suppressions to a group that has been deleted or does not exist, the suppressions will be added to the global suppressions list.

    Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /asm/groups/{group_id}/suppressions:
    get:
      summary: Get Asm Groups Group  Suppressions
      description: |-
        **This endpoint allows you to retrieve all suppressed email addresses belonging to the given group.**

        Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
      operationId: asm.groups.group_id.suppressions.get
      x-api-path-slug: asmgroupsgroup-idsuppressions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Asm
      - Groups
      - Group
      - ""
      - Suppressions
    post:
      summary: Add Asm Groups Group  Suppressions
      description: |-
        **This endpoint allows you to add email addresses to an unsubscribe group.**

        If you attempt to add suppressions to a group that has been deleted or does not exist, the suppressions will be added to the global suppressions list.

        Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
      operationId: asm.groups.group_id.suppressions.post
      x-api-path-slug: asmgroupsgroup-idsuppressions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Asm
      - Groups
      - Group
      - ""
      - Suppressions
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