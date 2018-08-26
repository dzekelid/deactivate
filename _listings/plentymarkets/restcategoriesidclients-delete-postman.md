{
  "info": {
    "name": "Plentymarkets Deactivate availability for clients",
    "_postman_id": "cab2d962-4321-483d-b601-368a0d9f010b",
    "description": "Deactivate availability for clients.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Deactivate",
      "item": [
        {
          "id": "5649b197-b624-4662-8956-d0f31928026a",
          "name": "deleteRestCategoriesClients",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/categories/:id/clients"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deactivate availability for clients."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c92f160-b1ce-49d3-a6de-44f85fae9126"
            }
          ]
        }
      ]
    }
  ]
}