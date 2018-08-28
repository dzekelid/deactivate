---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Deactivate a referrer account
  description: Deactivates a referrer account for a sales price.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/categories/{id}/clients:
    delete:
      summary: Deactivate availability for clients
      description: Deactivate availability for clients.
      operationId: deleteRestCategoriesClients
      x-api-path-slug: restcategoriesidclients-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Availabilityclients
  /rest/items/barcodes/{barcodeId}/referrer/{referrerId}:
    delete:
      summary: Deactivate a referrer
      description: Deactivate a referrer for a barcode. The ID of the barcode and
        the ID of the referrer must be specified.
      operationId: deleteRestItemsBarcodesBarcodeReferrerReferrer
      x-api-path-slug: restitemsbarcodesbarcodeidreferrerreferrerid-delete
      parameters:
      - in: path
        name: barcodeId
      - in: path
        name: referrerId
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Referrer
  /rest/items/sales_prices/{id}/accounts/{accountType}/{accountId}:
    delete:
      summary: Deactivate a referrer account
      description: Deactivates a referrer account for a sales price.
      operationId: deleteRestItemsSalesPricesAccountsAccounttypeAccount
      x-api-path-slug: restitemssales-pricesidaccountsaccounttypeaccountid-delete
      parameters:
      - in: path
        name: accountId
      - in: path
        name: accountType
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Referrer
      - Account
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