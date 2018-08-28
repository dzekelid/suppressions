{
  "info": {
    "name": "My Space Get Activities Supported Verbs",
    "_postman_id": "8f715029-8ff0-45f1-80ae-82b2168f7606",
    "description": "Retrieves all supported verbs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "709ec50a-0830-413d-9c83-1bbcdef40b35",
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
              "id": "2641e5fa-8281-412b-93a1-8bb2c1d92727"
            }
          ]
        },
        {
          "id": "01de9a66-b63b-402a-a33f-876fd7d000e5",
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
              "id": "99cf7592-656f-4531-90a1-ed20ae7dfc80"
            }
          ]
        },
        {
          "id": "d0c148e5-695f-4cb6-8509-6921b8a0419f",
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
              "id": "98dacfa0-7444-471c-95bf-cc725bf94122"
            }
          ]
        }
      ]
    }
  ]
}