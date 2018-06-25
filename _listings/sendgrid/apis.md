---
name: SendGrid
x-slug: sendgrid
description: Delivering your transactional and marketing emails through the worlds
  largest cloud-based email delivery platform. Send with confidence.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
x-kinRank: "9"
x-alexaRank: "10000"
tags: Suppressions
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid Get Asm Groups Group  Suppressions
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve all suppressed email addresses belonging to the given group.**

    Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/groups/{group_id}/suppressions
  tags: Email,Asm, Groups, Group, , Suppressions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressions-get-openapi.md
- name: SendGrid Add Asm Groups Group  Suppressions
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to add email addresses to an unsubscribe group.**

    If you attempt to add suppressions to a group that has been deleted or does not exist, the suppressions will be added to the global suppressions list.

    Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/groups/{group_id}/suppressions
  tags: Email,Asm, Groups, Group, , Suppressions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressions-post-openapi.md
- name: SendGrid Add Asm Groups Group  Suppressions Search
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to search a suppression group for multiple suppressions.**

    When given a list of email addresses and a group ID, this endpoint will return only the email addresses that have been unsubscribed from the given group.

    Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/groups/{group_id}/suppressions/search
  tags: Email,Asm, Groups, Group, , Suppressions, Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressionssearch-post-openapi.md
- name: SendGrid Delete Asm Groups Group  Suppressions Email
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to remove a suppressed email address from the given suppression group.**

    Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/groups/{group_id}/suppressions/{email}
  tags: Email,Asm, Groups, Group, , Suppressions, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmgroupsgroup-idsuppressionsemail-delete-openapi.md
- name: SendGrid Get Asm Suppressions
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a list of all suppressions.**

    Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/suppressions
  tags: Email,Asm, Suppressions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressions-get-openapi.md
- name: SendGrid Add Asm Suppressions Global
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to add one or more email addresses to the global suppressions group.**

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/suppressions/global
  tags: Email,Asm, Suppressions, Global
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressionsglobal-post-openapi.md
- name: SendGrid Delete Asm Suppressions Global Email
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to remove an email address from the global suppressions group.**

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/suppressions/global/{email}
  tags: Email,Asm, Suppressions, Global, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressionsglobalemail-delete-openapi.md
- name: SendGrid Get Asm Suppressions Global Email
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a global suppression. You can also use this endpoint to confirm if an email address is already globally suppresed.**

    If the email address you include in the URL path parameter `{email}` is alreayd globally suppressed, the response will include that email address. If the address you enter for `{email}` is not globally suppressed, an empty JSON object `{}` will be returned.

    A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/suppressions/global/{email}
  tags: Email,Asm, Suppressions, Global, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressionsglobalemail-get-openapi.md
- name: SendGrid Get Asm Suppressions Email
  x-api-slug: sendgrid
  description: |-
    **This endpoint returns the list of all groups that the given email address has been unsubscribed from.**

    Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//asm/suppressions/{email}
  tags: Email,Asm, Suppressions, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/asmsuppressionsemail-get-openapi.md
- name: SendGrid
  x-api-slug: sendgrid
  description: SendGrids cloud-based email infrastructure relieves businesses of the
    cost and complexity of maintaining custom email systems. SendGrid provides reliable
    delivery, scalability and real-time analytics along with flexible APIs that make
    custom integration a breeze.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: Suppressions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/suppressions/master/_listings/sendgrid/openapi.md
x-common:
- type: x--net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
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