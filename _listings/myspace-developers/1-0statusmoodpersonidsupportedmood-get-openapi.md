---
swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 0
info:
  title: My Space Get Statusmood Personid @supportedmood
  description: Retrieves all supported moods.
  version: 1.0.0
host: api.myspace.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1.0/statusmood/{personId}/@supportedMood/{moodId}:
    put:
      summary: Put Statusmood Personid @supportedmood Moodid
      description: Updates a mood.
      operationId: 1.0.statusmood.personId._supportedMood.moodId.put
      x-api-path-slug: 1-0statusmoodpersonidsupportedmoodmoodid-put
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: moodId
        description: The integer value of the specific mood that you want to retrieve
          data for
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Statusmood
      - People
      - Supported
      - Mood
      - MoodId
    get:
      summary: Get Statusmood Personid @supportedmood Moodid
      description: Retrieves a mood.
      operationId: 1.0.statusmood.personId._supportedMood.moodId.get
      x-api-path-slug: 1-0statusmoodpersonidsupportedmoodmoodid-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: moodId
        description: The integer value of the specific mood that you want to retrieve
          data for
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Statusmood
      - People
      - Supported
      - Mood
      - MoodId
  /1.0/statusmood/{personId}/@supportedMood:
    post:
      summary: Post Statusmood Personid @supportedmood
      description: Adds a mood.
      operationId: 1.0.statusmood.personId._supportedMood.post
      x-api-path-slug: 1-0statusmoodpersonidsupportedmood-post
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Statusmood
      - People
      - Supported
      - Mood
    get:
      summary: Get Statusmood Personid @supportedmood
      description: Retrieves all supported moods.
      operationId: 1.0.statusmood.personId._supportedMood.get
      x-api-path-slug: 1-0statusmoodpersonidsupportedmood-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Statusmood
      - People
      - Supported
      - Mood
  /1.0/mediaItems/{personId}/@videos/@supportedcategories/{categoryId}:
    get:
      summary: Get Mediaitems Personid Videos Supported Categories Categoryid
      description: Retrieves videos for Category.
      operationId: 1.0.mediaItems.personId._videos._supportedcategories.categoryId.get
      x-api-path-slug: 1-0mediaitemspersonidvideossupportedcategoriescategoryid-get
      parameters:
      - in: path
        name: categoryId
        description: Indicates the video category about which you want to retrieve
          data
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - '@videos'
      - Supported
      - categories
      - CategoryId
  /1.0/mediaItems/{personId}/@videos/@supportedcategories:
    get:
      summary: Get Mediaitems Personid Videos Supported Categories
      description: Retrieves supported categories.
      operationId: 1.0.mediaItems.personId._videos._supportedcategories.get
      x-api-path-slug: 1-0mediaitemspersonidvideossupportedcategories-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - '@videos'
      - Supported
      - categories
  /1.0/mediaItems/@supportedFields:
    get:
      summary: Get Mediaitems Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.mediaItems._supportedFields.get
      x-api-path-slug: 1-0mediaitemssupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - Supported
      - Fields
  /1.0/people/@supportedFields:
    get:
      summary: Get People Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.people._supportedFields.get
      x-api-path-slug: 1-0peoplesupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - People
      - Supported
      - Fields
  /1.0/groups/@supportedFields:
    get:
      summary: Get Groups Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.groups._supportedFields.get
      x-api-path-slug: 1-0groupssupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: 'The following field names are supported: id and title'
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Supported
      - Fields
  /1.0/albums/@supportedFields:
    get:
      summary: Get Albums Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.albums._supportedFields.get
      x-api-path-slug: 1-0albumssupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Albums
      - Supported
      - Fields
  /1.0/activities/@supportedObjectTypes:
    get:
      summary: Get Activities Supported Object Types
      description: Retrieves all supported object types.
      operationId: 1.0.activities._supportedObjectTypes.get
      x-api-path-slug: 1-0activitiessupportedobjecttypes-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      - in: query
        name: updatedSince
        description: Indicates the date before which no activities should be returned
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Supported
      - ObjectTypes
  /1.0/activities/@supportedVerbs:
    get:
      summary: Get Activities Supported Verbs
      description: Retrieves all supported verbs.
      operationId: 1.0.activities._supportedVerbs.get
      x-api-path-slug: 1-0activitiessupportedverbs-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      - in: query
        name: updatedSince
        description: Indicates the date before which no activities should be returned
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Supported
      - Verbs
  /1.0/activities/@supportedFields:
    get:
      summary: Get Activities Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.activities._supportedFields.get
      x-api-path-slug: 1-0activitiessupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      - in: query
        name: updatedSince
        description: Indicates the date before which no activities should be returned
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Supported
      - Fields
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