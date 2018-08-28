---
name: SendGrid
x-slug: sendgrid
description: Delivering your transactional and marketing emails through the worlds
  largest cloud-based email delivery platform. Send with confidence.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
x-kinRank: "9"
x-alexaRank: "10000"
tags: Suppressions
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid - Get Asm Groups Group  Suppressions
  x-api-slug: asmgroupsgroup-idsuppressions-get
  description: |-
    **This endpoint allows you to retrieve all suppressed email addresses belonging to the given group.**

    Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressions-get-openapi.md
- name: SendGrid - Add Asm Groups Group  Suppressions
  x-api-slug: asmgroupsgroup-idsuppressions-post
  description: |-
    **This endpoint allows you to add email addresses to an unsubscribe group.**

    If you attempt to add suppressions to a group that has been deleted or does not exist, the suppressions will be added to the global suppressions list.

    Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressions-post-openapi.md
- name: SendGrid - Add Asm Groups Group  Suppressions Search
  x-api-slug: asmgroupsgroup-idsuppressionssearch-post
  description: |-
    **This endpoint allows you to search a suppression group for multiple suppressions.**

    When given a list of email addresses and a group ID, this endpoint will return only the email addresses that have been unsubscribed from the given group.

    Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressionssearch-post-openapi.md
- name: SendGrid - Delete Asm Groups Group  Suppressions Email
  x-api-slug: asmgroupsgroup-idsuppressionsemail-delete
  description: |-
    **This endpoint allows you to remove a suppressed email address from the given suppression group.**

    Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressionsemail-delete-openapi.md
- name: SendGrid - Get Asm Suppressions
  x-api-slug: asmsuppressions-get
  description: |-
    **This endpoint allows you to retrieve a list of all suppressions.**

    Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressions-get-openapi.md
- name: SendGrid - Add Asm Suppressions Global
  x-api-slug: asmsuppressionsglobal-post
  description: |-
    **This endpoint allows you to add one or more email addresses to the global suppressions group.**

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressionsglobal-post-openapi.md
- name: SendGrid - Delete Asm Suppressions Global Email
  x-api-slug: asmsuppressionsglobalemail-delete
  description: |-
    **This endpoint allows you to remove an email address from the global suppressions group.**

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressionsglobalemail-delete-openapi.md
- name: SendGrid - Get Asm Suppressions Global Email
  x-api-slug: asmsuppressionsglobalemail-get
  description: |-
    **This endpoint allows you to retrieve a global suppression. You can also use this endpoint to confirm if an email address is already globally suppresed.**

    If the email address you include in the URL path parameter `{email}` is alreayd globally suppressed, the response will include that email address. If the address you enter for `{email}` is not globally suppressed, an empty JSON object `{}` will be returned.

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressionsglobalemail-get-openapi.md
- name: SendGrid - Get Asm Suppressions Email
  x-api-slug: asmsuppressionsemail-get
  description: |-
    **This endpoint returns the list of all groups that the given email address has been unsubscribed from.**

    Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressionsemail-get-openapi.md
- name: SendGrid - Delete Suppression Blocks
  x-api-slug: suppressionblocks-delete
  description: "**This endpoint allows you to delete all email addresses on your blocks
    list.**\n\nThere are two options for deleting blocked emails: \n\n1. You can delete
    all blocked emails by setting `delete_all` to true in the request body. \n2. You
    can delete some blocked emails by specifying the email addresses in an array in
    the request body.\n\n[Blocks](https://sendgrid.com/docs/Glossary/blocks.html)
    happen when your message was rejected for a reason related to the message, not
    the recipient address. This can happen when your mail server IP address has been
    added to a blacklist or blocked by an ISP, or if the message content is flagged
    by a filter on the receiving server.\n\nFor more information, please see our [User
    Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocks-delete-openapi.md
- name: SendGrid - Get Suppression Blocks
  x-api-slug: suppressionblocks-get
  description: |-
    **This endpoint allows you to retrieve a list of all email addresses that are currently on your blocks list.**

    There are several causes for [blocked](https://sendgrid.com/docs/Glossary/blocks.html) emails: for example, your mail server IP address is on an ISP blacklist, or blocked by an ISP, or if the receiving server flags the message content.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocks-get-openapi.md
- name: SendGrid - Delete Suppression Blocks Email
  x-api-slug: suppressionblocksemail-delete
  description: |-
    **This endpoint allows you to delete a specific email address from your blocks list.**

    [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocksemail-delete-openapi.md
- name: SendGrid - Get Suppression Blocks Email
  x-api-slug: suppressionblocksemail-get
  description: |-
    **This endpoint allows you to retrieve a specific email address from your blocks list.**

    [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocksemail-get-openapi.md
- name: SendGrid - Delete Suppression Bounces
  x-api-slug: suppressionbounces-delete
  description: "**This endpoint allows you to delete all of your bounces. You can
    also use this endpoint to remove a specific email address from your bounce list.**\n\nA
    bounced email is when the message is undeliverable and then returned to the server
    that sent it.\n\nFor more information see: \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)\n\nNote:
    the `delete_all` and `emails` parameters should be used independently of each
    other as they have different purposes."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-delete-openapi.md
- name: SendGrid - Get Suppression Bounces
  x-api-slug: suppressionbounces-get
  description: "**This endpoint allows you to retrieve all of your bounces.**\n\nA
    bounced email is when the message is undeliverable and then returned to the server
    that sent it.  \n\nFor more information see: \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-get-openapi.md
- name: SendGrid - Delete Suppression Bounces Email
  x-api-slug: suppressionbouncesemail-delete
  description: "**This endpoint allows you to remove an email address from your bounce
    list.**\n\nA bounced email is when the message is undeliverable and then returned
    to the server that sent it. This endpoint allows you to delete a single email
    addresses from your bounce list. \n\nFor more information see: \n\n* [User Guide
    > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html) for
    more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-delete-openapi.md
- name: SendGrid - Get Suppression Bounces Email
  x-api-slug: suppressionbouncesemail-get
  description: "**This endpoint allows you to retrieve a specific bounce for a given
    email address.**\n\nA bounced email is when the message is undeliverable and then
    returned to the server that sent it.\n\nFor more information see: \n\n* [User
    Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-get-openapi.md
- name: SendGrid - Delete Suppression Inval Emails
  x-api-slug: suppressioninvalid-emails-delete
  description: "**This endpoint allows you to remove email addresses from your invalid
    email address list.**\n\nThere are two options for deleting invalid email addresses:
    \n\n1) You can delete all invalid email addresses by setting `delete_all` to true
    in the request body.\n2) You can delete some invalid email addresses by specifying
    certain addresses in an array in the request body.\n\nAn invalid email occurs
    when you attempt to send email to an address that is formatted in a manner that
    does not meet internet email format standards or the email does not exist at the
    recipient???s mail server.\n\nExamples include addresses without the ???@??? sign
    or addresses that include certain special characters and/or spaces. This response
    can come from our own server or the recipient mail server.\n\nFor more information,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-delete-openapi.md
- name: SendGrid - Get Suppression Inval Emails
  x-api-slug: suppressioninvalid-emails-get
  description: |-
    **This endpoint allows you to retrieve a list of all invalid email addresses.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-get-openapi.md
- name: SendGrid - Delete Suppression Inval Emails Email
  x-api-slug: suppressioninvalid-emailsemail-delete
  description: |-
    **This endpoint allows you to remove a specific email address from the invalid email address list.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-delete-openapi.md
- name: SendGrid - Get Suppression Inval Emails Email
  x-api-slug: suppressioninvalid-emailsemail-get
  description: |-
    **This endpoint allows you to retrieve a specific invalid email addresses.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-get-openapi.md
- name: SendGrid - Delete Suppression Spam Reports
  x-api-slug: suppressionspam-reports-delete
  description: "**This endpoint allows you to delete your spam reports.**\n\nThere
    are two options for deleting spam reports: \n\n1) You can delete all spam reports
    by setting \"delete_all\" to true in the request body. \n2) You can delete some
    spam reports by specifying the email addresses in an array in the request body.\n\n[Spam
    reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient
    indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html)
    and then their email provider reports this to SendGrid.\n\nFor more information,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-delete-openapi.md
- name: SendGrid - Get Suppression Spam Reports
  x-api-slug: suppressionspam-reports-get
  description: |-
    **This endpoint allows you to retrieve all spam reports.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-get-openapi.md
- name: SendGrid - Delete Suppression Spam Reports Email
  x-api-slug: suppressionspam-reportsemail-delete
  description: |-
    **This endpoint allows you to delete a specific spam report.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-delete-openapi.md
- name: SendGrid - Get Suppression Spam Reports Email
  x-api-slug: suppressionspam-reportsemail-get
  description: |-
    **This endpoint allows you to retrieve a specific spam report.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-get-openapi.md
- name: SendGrid - Get Suppression Unsubscribes
  x-api-slug: suppressionunsubscribes-get
  description: |-
    **This endpoint allows you to retrieve a list of all email address that are globally suppressed.**

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionunsubscribes-get-openapi.md
- name: SendGrid - Delete Suppression Blocks
  x-api-slug: suppressionblocks-delete
  description: "**This endpoint allows you to delete all email addresses on your blocks
    list.**\n\nThere are two options for deleting blocked emails: \n\n1. You can delete
    all blocked emails by setting `delete_all` to true in the request body. \n2. You
    can delete some blocked emails by specifying the email addresses in an array in
    the request body.\n\n[Blocks](https://sendgrid.com/docs/Glossary/blocks.html)
    happen when your message was rejected for a reason related to the message, not
    the recipient address. This can happen when your mail server IP address has been
    added to a blacklist or blocked by an ISP, or if the message content is flagged
    by a filter on the receiving server.\n\nFor more information, please see our [User
    Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocks-delete-openapi.md
- name: SendGrid - Get Suppression Blocks
  x-api-slug: suppressionblocks-get
  description: |-
    **This endpoint allows you to retrieve a list of all email addresses that are currently on your blocks list.**

    There are several causes for [blocked](https://sendgrid.com/docs/Glossary/blocks.html) emails: for example, your mail server IP address is on an ISP blacklist, or blocked by an ISP, or if the receiving server flags the message content.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocks-get-openapi.md
- name: SendGrid - Delete Suppression Blocks Email
  x-api-slug: suppressionblocksemail-delete
  description: |-
    **This endpoint allows you to delete a specific email address from your blocks list.**

    [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocksemail-delete-openapi.md
- name: SendGrid - Get Suppression Blocks Email
  x-api-slug: suppressionblocksemail-get
  description: |-
    **This endpoint allows you to retrieve a specific email address from your blocks list.**

    [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocksemail-get-openapi.md
- name: SendGrid - Delete Suppression Bounces
  x-api-slug: suppressionbounces-delete
  description: "**This endpoint allows you to delete all of your bounces. You can
    also use this endpoint to remove a specific email address from your bounce list.**\n\nA
    bounced email is when the message is undeliverable and then returned to the server
    that sent it.\n\nFor more information see: \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)\n\nNote:
    the `delete_all` and `emails` parameters should be used independently of each
    other as they have different purposes."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-delete-openapi.md
- name: SendGrid - Get Suppression Bounces
  x-api-slug: suppressionbounces-get
  description: "**This endpoint allows you to retrieve all of your bounces.**\n\nA
    bounced email is when the message is undeliverable and then returned to the server
    that sent it.  \n\nFor more information see: \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-get-openapi.md
- name: SendGrid - Delete Suppression Bounces Email
  x-api-slug: suppressionbouncesemail-delete
  description: "**This endpoint allows you to remove an email address from your bounce
    list.**\n\nA bounced email is when the message is undeliverable and then returned
    to the server that sent it. This endpoint allows you to delete a single email
    addresses from your bounce list. \n\nFor more information see: \n\n* [User Guide
    > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html) for
    more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-delete-openapi.md
- name: SendGrid - Get Suppression Bounces Email
  x-api-slug: suppressionbouncesemail-get
  description: "**This endpoint allows you to retrieve a specific bounce for a given
    email address.**\n\nA bounced email is when the message is undeliverable and then
    returned to the server that sent it.\n\nFor more information see: \n\n* [User
    Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-get-openapi.md
- name: SendGrid - Delete Suppression Inval Emails
  x-api-slug: suppressioninvalid-emails-delete
  description: "**This endpoint allows you to remove email addresses from your invalid
    email address list.**\n\nThere are two options for deleting invalid email addresses:
    \n\n1) You can delete all invalid email addresses by setting `delete_all` to true
    in the request body.\n2) You can delete some invalid email addresses by specifying
    certain addresses in an array in the request body.\n\nAn invalid email occurs
    when you attempt to send email to an address that is formatted in a manner that
    does not meet internet email format standards or the email does not exist at the
    recipient???s mail server.\n\nExamples include addresses without the ???@??? sign
    or addresses that include certain special characters and/or spaces. This response
    can come from our own server or the recipient mail server.\n\nFor more information,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-delete-openapi.md
- name: SendGrid - Get Suppression Inval Emails
  x-api-slug: suppressioninvalid-emails-get
  description: |-
    **This endpoint allows you to retrieve a list of all invalid email addresses.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-get-openapi.md
- name: SendGrid - Delete Suppression Inval Emails Email
  x-api-slug: suppressioninvalid-emailsemail-delete
  description: |-
    **This endpoint allows you to remove a specific email address from the invalid email address list.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-delete-openapi.md
- name: SendGrid - Get Suppression Inval Emails Email
  x-api-slug: suppressioninvalid-emailsemail-get
  description: |-
    **This endpoint allows you to retrieve a specific invalid email addresses.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-get-openapi.md
- name: SendGrid - Delete Suppression Spam Reports
  x-api-slug: suppressionspam-reports-delete
  description: "**This endpoint allows you to delete your spam reports.**\n\nThere
    are two options for deleting spam reports: \n\n1) You can delete all spam reports
    by setting \"delete_all\" to true in the request body. \n2) You can delete some
    spam reports by specifying the email addresses in an array in the request body.\n\n[Spam
    reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient
    indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html)
    and then their email provider reports this to SendGrid.\n\nFor more information,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-delete-openapi.md
- name: SendGrid - Get Suppression Spam Reports
  x-api-slug: suppressionspam-reports-get
  description: |-
    **This endpoint allows you to retrieve all spam reports.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-get-openapi.md
- name: SendGrid - Delete Suppression Spam Reports Email
  x-api-slug: suppressionspam-reportsemail-delete
  description: |-
    **This endpoint allows you to delete a specific spam report.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-delete-openapi.md
- name: SendGrid - Get Suppression Spam Reports Email
  x-api-slug: suppressionspam-reportsemail-get
  description: |-
    **This endpoint allows you to retrieve a specific spam report.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-get-openapi.md
- name: SendGrid - Get Suppression Unsubscribes
  x-api-slug: suppressionunsubscribes-get
  description: |-
    **This endpoint allows you to retrieve a list of all email address that are globally suppressed.**

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionunsubscribes-get-openapi.md
- name: SendGrid - Get Suppression Unsubscribes
  x-api-slug: suppressionunsubscribes-get
  description: |-
    **This endpoint allows you to retrieve a list of all email address that are globally suppressed.**

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionunsubscribes-get-openapi.md
- name: SendGrid - Get Suppression Spam Reports Email
  x-api-slug: suppressionspam-reportsemail-get
  description: |-
    **This endpoint allows you to retrieve a specific spam report.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-get-openapi.md
- name: SendGrid - Delete Suppression Spam Reports Email
  x-api-slug: suppressionspam-reportsemail-delete
  description: |-
    **This endpoint allows you to delete a specific spam report.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reportsemail-delete-openapi.md
- name: SendGrid - Get Suppression Spam Reports
  x-api-slug: suppressionspam-reports-get
  description: |-
    **This endpoint allows you to retrieve all spam reports.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-get-openapi.md
- name: SendGrid - Delete Suppression Spam Reports
  x-api-slug: suppressionspam-reports-delete
  description: "**This endpoint allows you to delete your spam reports.**\n\nThere
    are two options for deleting spam reports: \n\n1) You can delete all spam reports
    by setting \"delete_all\" to true in the request body. \n2) You can delete some
    spam reports by specifying the email addresses in an array in the request body.\n\n[Spam
    reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient
    indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html)
    and then their email provider reports this to SendGrid.\n\nFor more information,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionspam-reports-delete-openapi.md
- name: SendGrid - Get Suppression Inval Emails Email
  x-api-slug: suppressioninvalid-emailsemail-get
  description: |-
    **This endpoint allows you to retrieve a specific invalid email addresses.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-get-openapi.md
- name: SendGrid - Delete Suppression Inval Emails Email
  x-api-slug: suppressioninvalid-emailsemail-delete
  description: |-
    **This endpoint allows you to remove a specific email address from the invalid email address list.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emailsemail-delete-openapi.md
- name: SendGrid - Get Suppression Inval Emails
  x-api-slug: suppressioninvalid-emails-get
  description: |-
    **This endpoint allows you to retrieve a list of all invalid email addresses.**

    An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient???s mail server.

    Examples include addresses without the ???@??? sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-get-openapi.md
- name: SendGrid - Delete Suppression Inval Emails
  x-api-slug: suppressioninvalid-emails-delete
  description: "**This endpoint allows you to remove email addresses from your invalid
    email address list.**\n\nThere are two options for deleting invalid email addresses:
    \n\n1) You can delete all invalid email addresses by setting `delete_all` to true
    in the request body.\n2) You can delete some invalid email addresses by specifying
    certain addresses in an array in the request body.\n\nAn invalid email occurs
    when you attempt to send email to an address that is formatted in a manner that
    does not meet internet email format standards or the email does not exist at the
    recipient???s mail server.\n\nExamples include addresses without the ???@??? sign
    or addresses that include certain special characters and/or spaces. This response
    can come from our own server or the recipient mail server.\n\nFor more information,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressioninvalid-emails-delete-openapi.md
- name: SendGrid - Get Suppression Bounces Email
  x-api-slug: suppressionbouncesemail-get
  description: "**This endpoint allows you to retrieve a specific bounce for a given
    email address.**\n\nA bounced email is when the message is undeliverable and then
    returned to the server that sent it.\n\nFor more information see: \n\n* [User
    Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-get-openapi.md
- name: SendGrid - Delete Suppression Bounces Email
  x-api-slug: suppressionbouncesemail-delete
  description: "**This endpoint allows you to remove an email address from your bounce
    list.**\n\nA bounced email is when the message is undeliverable and then returned
    to the server that sent it. This endpoint allows you to delete a single email
    addresses from your bounce list. \n\nFor more information see: \n\n* [User Guide
    > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html) for
    more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbouncesemail-delete-openapi.md
- name: SendGrid - Get Suppression Bounces
  x-api-slug: suppressionbounces-get
  description: "**This endpoint allows you to retrieve all of your bounces.**\n\nA
    bounced email is when the message is undeliverable and then returned to the server
    that sent it.  \n\nFor more information see: \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-get-openapi.md
- name: SendGrid - Delete Suppression Bounces
  x-api-slug: suppressionbounces-delete
  description: "**This endpoint allows you to delete all of your bounces. You can
    also use this endpoint to remove a specific email address from your bounce list.**\n\nA
    bounced email is when the message is undeliverable and then returned to the server
    that sent it.\n\nFor more information see: \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)\n\nNote:
    the `delete_all` and `emails` parameters should be used independently of each
    other as they have different purposes."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionbounces-delete-openapi.md
- name: SendGrid - Get Suppression Blocks Email
  x-api-slug: suppressionblocksemail-get
  description: |-
    **This endpoint allows you to retrieve a specific email address from your blocks list.**

    [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocksemail-get-openapi.md
- name: SendGrid - Delete Suppression Blocks Email
  x-api-slug: suppressionblocksemail-delete
  description: |-
    **This endpoint allows you to delete a specific email address from your blocks list.**

    [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocksemail-delete-openapi.md
- name: SendGrid - Get Suppression Blocks
  x-api-slug: suppressionblocks-get
  description: |-
    **This endpoint allows you to retrieve a list of all email addresses that are currently on your blocks list.**

    There are several causes for [blocked](https://sendgrid.com/docs/Glossary/blocks.html) emails: for example, your mail server IP address is on an ISP blacklist, or blocked by an ISP, or if the receiving server flags the message content.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocks-get-openapi.md
- name: SendGrid - Delete Suppression Blocks
  x-api-slug: suppressionblocks-delete
  description: "**This endpoint allows you to delete all email addresses on your blocks
    list.**\n\nThere are two options for deleting blocked emails: \n\n1. You can delete
    all blocked emails by setting `delete_all` to true in the request body. \n2. You
    can delete some blocked emails by specifying the email addresses in an array in
    the request body.\n\n[Blocks](https://sendgrid.com/docs/Glossary/blocks.html)
    happen when your message was rejected for a reason related to the message, not
    the recipient address. This can happen when your mail server IP address has been
    added to a blacklist or blocked by an ISP, or if the message content is flagged
    by a filter on the receiving server.\n\nFor more information, please see our [User
    Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/suppressionblocks-delete-openapi.md
x-common:
- type: x--net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-api-gallery
  url: http://school.digger.api.gallery.streamdata.io
- type: x-api-stack
  url: http://sendgrid.stack.network
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-crunchbase
  url: https://crunchbase.com/organization/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-email
  url: privacy@sendgrid.com
- type: x-email
  url: legal@sendgrid.com
- type: x-email
  url: dpo@sendgrid.com
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-linkedin
  url: https://www.linkedin.com/company/sendgrid
- type: x-node-js-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: http://sendgrid.com
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---