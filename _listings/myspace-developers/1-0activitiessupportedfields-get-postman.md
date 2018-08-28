{
  "info": {
    "name": "My Space Get Activities Supported Fields",
    "_postman_id": "187b8416-7df1-4743-a61d-ed397ddb0547",
    "description": "Retrieves all supported fields.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "e60d0e18-50c5-4327-968a-891efcabafa7",
          "name": "1.0.activities.personId.selector.appId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/activities/:personId/:selector/:appId"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "updatedSince",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "appId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "selector",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves activities created by an application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c83eec57-ee22-4d7f-b31e-0b8978fca498"
            }
          ]
        },
        {
          "id": "2ef229df-0a4f-49fb-96c8-0aeb3ef9ce12",
          "name": "1.0.activities._supportedObjectTypes.get",
          "request": {
            "url": "http://api.myspace.com/1.0/activities/@supportedObjectTypes?count=%7B%7D&fields=%7B%7D&format=%7B%7D&startIndex=%7B%7D&updatedSince=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported object types."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "745b694a-839a-441a-b3f7-1ba5762cd8c6"
            }
          ]
        },
        {
          "id": "2b1c7949-1614-495a-a860-1e797e522212",
          "name": "1.0.activities._supportedVerbs.get",
          "request": {
            "url": "http://api.myspace.com/1.0/activities/@supportedVerbs?count=%7B%7D&fields=%7B%7D&format=%7B%7D&startIndex=%7B%7D&updatedSince=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported verbs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ecd7d3b7-10a4-457e-9595-da0073569136"
            }
          ]
        },
        {
          "id": "f3f77035-7b25-4e09-98cb-01754507dd5b",
          "name": "1.0.activities._supportedFields.get",
          "request": {
            "url": "http://api.myspace.com/1.0/activities/@supportedFields?count=%7B%7D&fields=%7B%7D&format=%7B%7D&startIndex=%7B%7D&updatedSince=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported fields."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77ec371b-178a-40b5-a4e5-5605dc87c1ad"
            }
          ]
        }
      ]
    }
  ]
}