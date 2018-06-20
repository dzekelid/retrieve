---
swagger: "2.0"
x-collection-name: taxamo
x-complete: 0
info:
  title: Taxamo Retrieve Transaction Data.
  description: Retrieve transaction data..
  version: "1"
host: api.taxamo.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/transactions/{key}:
    get:
      summary: Retrieve Transaction Data.
      description: Retrieve transaction data..
      operationId: getTransaction
      x-api-path-slug: apiv1transactionskey-get
      parameters:
      - in: path
        name: key
        description: Transaction key
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Transaction
      - Data
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