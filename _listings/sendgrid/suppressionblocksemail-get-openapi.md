---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Get Suppression Blocks Email
  description: |-
    **This endpoint allows you to retrieve a specific email address from your blocks list.**

    [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
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
  /asm/groups/{group_id}/suppressions/search:
    post:
      summary: Add Asm Groups Group  Suppressions Search
      description: |-
        **This endpoint allows you to search a suppression group for multiple suppressions.**

        When given a list of email addresses and a group ID, this endpoint will return only the email addresses that have been unsubscribed from the given group.

        Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
      operationId: asm.groups.group_id.suppressions.search.post
      x-api-path-slug: asmgroupsgroup-idsuppressionssearch-post
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
      - Search
  /asm/groups/{group_id}/suppressions/{email}:
    delete:
      summary: Delete Asm Groups Group  Suppressions Email
      description: |-
        **This endpoint allows you to remove a suppressed email address from the given suppression group.**

        Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
      operationId: asm.groups.group_id.suppressions.email.delete
      x-api-path-slug: asmgroupsgroup-idsuppressionsemail-delete
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
      - Email
  /asm/suppressions:
    get:
      summary: Get Asm Suppressions
      description: |-
        **This endpoint allows you to retrieve a list of all suppressions.**

        Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
      operationId: asm.suppressions.get
      x-api-path-slug: asmsuppressions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Asm
      - Suppressions
  /asm/suppressions/global:
    post:
      summary: Add Asm Suppressions Global
      description: |-
        **This endpoint allows you to add one or more email addresses to the global suppressions group.**

        A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
      operationId: asm.suppressions.global.post
      x-api-path-slug: asmsuppressionsglobal-post
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
      - Suppressions
      - Global
  /asm/suppressions/global/{email}:
    delete:
      summary: Delete Asm Suppressions Global Email
      description: |-
        **This endpoint allows you to remove an email address from the global suppressions group.**

        A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
      operationId: asm.suppressions.global.email.delete
      x-api-path-slug: asmsuppressionsglobalemail-delete
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
      - Suppressions
      - Global
      - Email
    get:
      summary: Get Asm Suppressions Global Email
      description: |-
        **This endpoint allows you to retrieve a global suppression. You can also use this endpoint to confirm if an email address is already globally suppresed.**

        If the email address you include in the URL path parameter `{email}` is alreayd globally suppressed, the response will include that email address. If the address you enter for `{email}` is not globally suppressed, an empty JSON object `{}` will be returned.

        A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
      operationId: asm.suppressions.global.email.get
      x-api-path-slug: asmsuppressionsglobalemail-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Asm
      - Suppressions
      - Global
      - Email
  /asm/suppressions/{email}:
    get:
      summary: Get Asm Suppressions Email
      description: |-
        **This endpoint returns the list of all groups that the given email address has been unsubscribed from.**

        Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
      operationId: asm.suppressions.email.get
      x-api-path-slug: asmsuppressionsemail-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Asm
      - Suppressions
      - Email
  /suppression/blocks:
    delete:
      summary: Delete Suppression Blocks
      description: "**This endpoint allows you to delete all email addresses on your
        blocks list.**\n\nThere are two options for deleting blocked emails: \n\n1.
        You can delete all blocked emails by setting `delete_all` to true in the request
        body. \n2. You can delete some blocked emails by specifying the email addresses
        in an array in the request body.\n\n[Blocks](https://sendgrid.com/docs/Glossary/blocks.html)
        happen when your message was rejected for a reason related to the message,
        not the recipient address. This can happen when your mail server IP address
        has been added to a blacklist or blocked by an ISP, or if the message content
        is flagged by a filter on the receiving server.\n\nFor more information, please
        see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html)."
      operationId: suppression.blocks.delete
      x-api-path-slug: suppressionblocks-delete
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
      - Suppression
      - Blocks
    get:
      summary: Get Suppression Blocks
      description: |-
        **This endpoint allows you to retrieve a list of all email addresses that are currently on your blocks list.**

        There are several causes for [blocked](https://sendgrid.com/docs/Glossary/blocks.html) emails: for example, your mail server IP address is on an ISP blacklist, or blocked by an ISP, or if the receiving server flags the message content.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
      operationId: suppression.blocks.get
      x-api-path-slug: suppressionblocks-get
      parameters:
      - in: query
        name: end_time
        description: Refers end of the time range in unix timestamp when a blocked
          email was created (inclusive)
      - in: query
        name: limit
        description: Limit the number of results to be displayed per page
      - in: query
        name: No Name
      - in: query
        name: offset
        description: The point in the list to begin displaying results
      - in: query
        name: start_time
        description: Refers start of the time range in unix timestamp when a blocked
          email was created (inclusive)
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Blocks
  /suppression/blocks/{email}:
    delete:
      summary: Delete Suppression Blocks Email
      description: |-
        **This endpoint allows you to delete a specific email address from your blocks list.**

        [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
      operationId: suppression.blocks.email.delete
      x-api-path-slug: suppressionblocksemail-delete
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
      - Suppression
      - Blocks
      - Email
    get:
      summary: Get Suppression Blocks Email
      description: |-
        **This endpoint allows you to retrieve a specific email address from your blocks list.**

        [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
      operationId: suppression.blocks.email.get
      x-api-path-slug: suppressionblocksemail-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Blocks
      - Email
  /suppression/bounces:
    delete:
      summary: Delete Suppression Bounces
      description: "**This endpoint allows you to delete all of your bounces. You
        can also use this endpoint to remove a specific email address from your bounce
        list.**\n\nA bounced email is when the message is undeliverable and then returned
        to the server that sent it.\n\nFor more information see: \n\n* [User Guide
        > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
        for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
        [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)\n\nNote:
        the `delete_all` and `emails` parameters should be used independently of each
        other as they have different purposes."
      operationId: suppression.bounces.delete
      x-api-path-slug: suppressionbounces-delete
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
      - Suppression
      - Bounces
    get:
      summary: Get Suppression Bounces
      description: "**This endpoint allows you to retrieve all of your bounces.**\n\nA
        bounced email is when the message is undeliverable and then returned to the
        server that sent it.  \n\nFor more information see: \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
        for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)"
      operationId: suppression.bounces.get
      x-api-path-slug: suppressionbounces-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: end_time
        description: Refers end of the time range in unix timestamp when a bounce
          was created (inclusive)
      - in: query
        name: No Name
      - in: query
        name: start_time
        description: Refers start of the time range in unix timestamp when a bounce
          was created (inclusive)
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Bounces
  /suppression/bounces/{email}:
    delete:
      summary: Delete Suppression Bounces Email
      description: "**This endpoint allows you to remove an email address from your
        bounce list.**\n\nA bounced email is when the message is undeliverable and
        then returned to the server that sent it. This endpoint allows you to delete
        a single email addresses from your bounce list. \n\nFor more information see:
        \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
        for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
        [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)"
      operationId: suppression.bounces.email.delete
      x-api-path-slug: suppressionbouncesemail-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: email_address
        description: The email address you would like to remove from the bounce list
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Bounces
      - Email
    get:
      summary: Get Suppression Bounces Email
      description: "**This endpoint allows you to retrieve a specific bounce for a
        given email address.**\n\nA bounced email is when the message is undeliverable
        and then returned to the server that sent it.\n\nFor more information see:
        \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
        for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
        [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)"
      operationId: suppression.bounces.email.get
      x-api-path-slug: suppressionbouncesemail-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Bounces
      - Email
  /suppression/invalid_emails:
    delete:
      summary: Delete Suppression Inval Emails
      description: "**This endpoint allows you to remove email addresses from your
        invalid email address list.**\n\nThere are two options for deleting invalid
        email addresses: \n\n1) You can delete all invalid email addresses by setting
        `delete_all` to true in the request body.\n2) You can delete some invalid
        email addresses by specifying certain addresses in an array in the request
        body.\n\nAn invalid email occurs when you attempt to send email to an address
        that is formatted in a manner that does not meet internet email format standards
        or the email does not exist at the recipient???s mail server.\n\nExamples
        include addresses without the ???@??? sign or addresses that include certain
        special characters and/or spaces. This response can come from our own server
        or the recipient mail server.\n\nFor more information, please see our [User
        Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html)."
      operationId: suppression.invalid_emails.delete
      x-api-path-slug: suppressioninvalid-emails-delete
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
      - Suppression
      - Inval
      - Emails
    get:
      summary: Get Suppression Inval Emails
      description: |-
        **This endpoint allows you to retrieve a list of all invalid email addresses.**

        An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

        Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
      operationId: suppression.invalid_emails.get
      x-api-path-slug: suppressioninvalid-emails-get
      parameters:
      - in: query
        name: end_time
        description: Refers end of the time range in unix timestamp when an invalid
          email was created (inclusive)
      - in: query
        name: limit
        description: Limit the number of results to be displayed per page
      - in: query
        name: No Name
      - in: query
        name: offset
        description: Paging offset
      - in: query
        name: start_time
        description: Refers start of the time range in unix timestamp when an invalid
          email was created (inclusive)
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Inval
      - Emails
  /suppression/invalid_emails/{email}:
    delete:
      summary: Delete Suppression Inval Emails Email
      description: |-
        **This endpoint allows you to remove a specific email address from the invalid email address list.**

        An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

        Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
      operationId: suppression.invalid_emails.email.delete
      x-api-path-slug: suppressioninvalid-emailsemail-delete
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
      - Suppression
      - Inval
      - Emails
      - Email
    get:
      summary: Get Suppression Inval Emails Email
      description: |-
        **This endpoint allows you to retrieve a specific invalid email addresses.**

        An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

        Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
      operationId: suppression.invalid_emails.email.get
      x-api-path-slug: suppressioninvalid-emailsemail-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Inval
      - Emails
      - Email
  /suppression/spam_reports:
    delete:
      summary: Delete Suppression Spam Reports
      description: "**This endpoint allows you to delete your spam reports.**\n\nThere
        are two options for deleting spam reports: \n\n1) You can delete all spam
        reports by setting \"delete_all\" to true in the request body. \n2) You can
        delete some spam reports by specifying the email addresses in an array in
        the request body.\n\n[Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html)
        happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html)
        and then their email provider reports this to SendGrid.\n\nFor more information,
        please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html)."
      operationId: suppression.spam_reports.delete
      x-api-path-slug: suppressionspam-reports-delete
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
      - Suppression
      - Spam
      - Reports
    get:
      summary: Get Suppression Spam Reports
      description: |-
        **This endpoint allows you to retrieve all spam reports.**

        [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
      operationId: suppression.spam_reports.get
      x-api-path-slug: suppressionspam-reports-get
      parameters:
      - in: query
        name: end_time
        description: Refers end of the time range in unix timestamp when a spam report
          was created (inclusive)
      - in: query
        name: limit
        description: Limit the number of results to be displayed per page
      - in: query
        name: No Name
      - in: query
        name: offset
        description: Paging offset
      - in: query
        name: start_time
        description: Refers start of the time range in unix timestamp when a spam
          report was created (inclusive)
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Spam
      - Reports
  /suppression/spam_reports/{email}:
    delete:
      summary: Delete Suppression Spam Reports Email
      description: |-
        **This endpoint allows you to delete a specific spam report.**

        [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
      operationId: suppression.spam_reports.email.delete
      x-api-path-slug: suppressionspam-reportsemail-delete
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
      - Suppression
      - Spam
      - Reports
      - Email
    get:
      summary: Get Suppression Spam Reports Email
      description: |-
        **This endpoint allows you to retrieve a specific spam report.**

        [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

        For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
      operationId: suppression.spam_reports.email.get
      x-api-path-slug: suppressionspam-reportsemail-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Spam
      - Reports
      - Email
  /suppression/unsubscribes:
    get:
      summary: Get Suppression Unsubscribes
      description: |-
        **This endpoint allows you to retrieve a list of all email address that are globally suppressed.**

        A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
      operationId: suppression.unsubscribes.get
      x-api-path-slug: suppressionunsubscribes-get
      parameters:
      - in: query
        name: end_time
        description: Refers end of the time range in unix timestamp when an unsubscribe
          email was created (inclusive)
      - in: query
        name: limit
        description: The number of results to display on each page
      - in: query
        name: No Name
      - in: query
        name: offset
        description: The point in the list of results to begin displaying global suppressions
      - in: query
        name: start_time
        description: Refers start of the time range in unix timestamp when an unsubscribe
          email was created (inclusive)
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Unsubscribes
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