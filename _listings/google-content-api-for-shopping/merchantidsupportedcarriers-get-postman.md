{
  "info": {
    "name": "Google Content API for Shopping API Get Supported Carriers",
    "_postman_id": "a922cbb2-37ef-4ba8-b494-cf64f8d30078",
    "description": "Retrieves supported carriers and carrier services for an account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "supported",
      "item": [
        {
          "id": "47f329ce-993c-438f-ab0a-bbfd9b8e848a",
          "name": "content.shippingsettings.getsupportedcarriers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "content",
                "v2",
                ":merchantId/supportedCarriers"
              ],
              "variable": [
                {
                  "id": "merchantId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves supported carriers and carrier services for an account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a37da694-bd50-477d-ac28-f423b8f0e4e9"
            }
          ]
        }
      ]
    }
  ]
}