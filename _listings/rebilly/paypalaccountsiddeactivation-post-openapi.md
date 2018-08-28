---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Deactivate a PayPal Account
  description: Deactivate a PayPal Account
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /bank-accounts/{id}/deactivation:
    post:
      summary: Deactivate a Bank Account
      description: Deactivate a Bank Account
      operationId: bank_accounts.id.deactivation.post
      x-api-path-slug: bankaccountsiddeactivation-post
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Bank
      - Account
  /payment-cards/{id}/deactivation:
    post:
      summary: Deactivate a Payment Card
      description: Deactivate a Payment Card
      operationId: payment_cards.id.deactivation.post
      x-api-path-slug: paymentcardsiddeactivation-post
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Payment
      - Card
  /paypal-accounts/{id}/deactivation:
    post:
      summary: Deactivate a PayPal Account
      description: Deactivate a PayPal Account
      operationId: paypal_accounts.id.deactivation.post
      x-api-path-slug: paypalaccountsiddeactivation-post
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - PayPal
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