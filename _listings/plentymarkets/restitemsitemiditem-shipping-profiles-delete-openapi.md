---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Deactivate shipping profiles of an item
  description: Deactivates all shipping profiles of an item. The ID of the item must
    be specified.
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
  /rest/items/sales_prices/{id}/countries/{countryId}:
    delete:
      summary: Deactivate a country
      description: Deactivates a country for a sales price.
      operationId: deleteRestItemsSalesPricesCountriesCountry
      x-api-path-slug: restitemssales-pricesidcountriescountryid-delete
      parameters:
      - in: path
        name: countryId
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Country
  /rest/items/sales_prices/{id}/currencies/{currency}:
    delete:
      summary: Deactivate a currency
      description: Deactivate a currency for a sales price. The ID of the sales price
        and the ISO code of the currency must be specified.
      operationId: deleteRestItemsSalesPricesCurrenciesCurrency
      x-api-path-slug: restitemssales-pricesidcurrenciescurrency-delete
      parameters:
      - in: path
        name: currency
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Currency
  /rest/items/sales_prices/{id}/online_stores/{webstoreId}:
    delete:
      summary: Deactivate a client (store)
      description: Deactivates a client (store) for a sales price. The ID of the sales
        price and the ID of the client (store) must be specified.
      operationId: deleteRestItemsSalesPricesOnlineStoresWebstore
      x-api-path-slug: restitemssales-pricesidonline-storeswebstoreid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: webstoreId
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Client
      - (store)
  /rest/items/{itemId}/item_shipping_profiles:
    delete:
      summary: Deactivate shipping profiles of an item
      description: Deactivates all shipping profiles of an item. The ID of the item
        must be specified.
      operationId: deleteRestItemsItemItemShippingProfiles
      x-api-path-slug: restitemsitemiditem-shipping-profiles-delete
      parameters:
      - in: path
        name: itemId
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Shipping
      - Profiles
      - Of
      - Item
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