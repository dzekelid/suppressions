swagger: "2.0"
x-collection-name: Azure Advisor
x-complete: 1
info:
  title: Azure Advisor API
  description: azure-advisor-is-a-personalized-recommendation-engine-that-helps-you-follow-azure-best-practices--it-analyzes-your-azure-resource-configuration-and-usage-telemetry-then-provides-recommendations-that-can-reduce-costs-and-improve-the-performance-security-and-reliability-of-your-applications-
  version: "2017-04-19"
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{resourceUri}/providers/Microsoft.Advisor/recommendations/{recommendationId}/suppressions/{name}:
    get:
      summary: Get Suppressions
      description: Obtains the details of a suppression.
      operationId: Suppressions_Get
      x-api-path-slug: resourceuriprovidersmicrosoft-advisorrecommendationsrecommendationidsuppressionsname-get
      parameters:
      - in: path
        name: name
        description: The name of the suppression
      - in: query
        name: No Name
      - in: path
        name: recommendationId
        description: The recommendation ID
      - in: path
        name: resourceUri
        description: The fully qualified Azure Resource Manager identifier of the
          resource to which the recommendation applies
      responses:
        200:
          description: OK
      tags:
      - Suppressions
    put:
      summary: Create Suppressions
      description: Enables the snoozed or dismissed attribute of a recommendation.
        The snoozed or dismissed attribute is referred to as a suppression. Use this
        API to create or update the snoozed or dismissed status of a recommendation.
      operationId: Suppressions_Create
      x-api-path-slug: resourceuriprovidersmicrosoft-advisorrecommendationsrecommendationidsuppressionsname-put
      parameters:
      - in: path
        name: name
        description: The name of the suppression
      - in: query
        name: No Name
      - in: path
        name: recommendationId
        description: The recommendation ID
      - in: path
        name: resourceUri
        description: The fully qualified Azure Resource Manager identifier of the
          resource to which the recommendation applies
      - in: body
        name: suppressionContract
        description: The snoozed or dismissed attribute; for example, the snooze duration
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Suppressions
    delete:
      summary: Delete Suppressions
      description: Enables the activation of a snoozed or dismissed recommendation.
        The snoozed or dismissed attribute of a recommendation is referred to as a
        suppression.
      operationId: Suppressions_Delete
      x-api-path-slug: resourceuriprovidersmicrosoft-advisorrecommendationsrecommendationidsuppressionsname-delete
      parameters:
      - in: path
        name: name
        description: The name of the suppression
      - in: query
        name: No Name
      - in: path
        name: recommendationId
        description: The recommendation ID
      - in: path
        name: resourceUri
        description: The fully qualified Azure Resource Manager identifier of the
          resource to which the recommendation applies
      responses:
        200:
          description: OK
      tags:
      - Suppressions
  /subscriptions/{subscriptionId}/providers/Microsoft.Advisor/suppressions:
    get:
      summary: List Suppressions
      description: Retrieves the list of snoozed or dismissed suppressions for a subscription.
        The snoozed or dismissed attribute of a recommendation is referred to as a
        suppression.
      operationId: Suppressions_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-advisorsuppressions-get
      parameters:
      - in: query
        name: $skipToken
        description: The page-continuation token to use with a paged version of this
          API
      - in: query
        name: $top
        description: The number of suppressions per page if a paged version of this
          API is being used
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Suppressions