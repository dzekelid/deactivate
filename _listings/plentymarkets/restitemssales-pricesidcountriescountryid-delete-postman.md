{
  "info": {
    "name": "Plentymarkets Deactivate a country",
    "_postman_id": "e7582e1f-a329-48b5-9ec1-c852fe4695a9",
    "description": "Deactivates a country for a sales price.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Deactivate",
      "item": [
        {
          "id": "2cab193b-58ae-47df-9b1c-7539bb16a13d",
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
              "id": "06452d49-1830-446c-9be8-d148ba592fa1"
            }
          ]
        },
        {
          "id": "9afd70e7-81d4-493a-9e7d-eacd26c1e8c6",
          "name": "deleteRestItemsBarcodesBarcodeReferrerReferrer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/barcodes/:barcodeId/referrer/:referrerId"
              ],
              "variable": [
                {
                  "id": "barcodeId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "referrerId",
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
            "description": "Deactivate a referrer for a barcode. The ID of the barcode and the ID of the referrer must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "747701ac-9081-4a90-8c53-ed911ab4810c"
            }
          ]
        },
        {
          "id": "970167af-f52a-4dbb-946c-548929ea518a",
          "name": "deleteRestItemsSalesPricesAccountsAccounttypeAccount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/sales_prices/:id/accounts/:accountType/:accountId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "accountType",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Deactivates a referrer account for a sales price."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d47784a2-c5f1-4f10-8ebe-09e045a14d9f"
            }
          ]
        },
        {
          "id": "25cfd83e-cf59-439a-9efa-f14863521798",
          "name": "deleteRestItemsSalesPricesCountriesCountry",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/sales_prices/:id/countries/:countryId"
              ],
              "variable": [
                {
                  "id": "countryId",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Deactivates a country for a sales price."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94166814-47d0-4bb8-b117-f2791ebbca41"
            }
          ]
        }
      ]
    }
  ]
}