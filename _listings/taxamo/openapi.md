---
swagger: "2.0"
x-collection-name: taxamo
x-complete: 1
info:
  title: Taxamo
  description: taxamos-elegant-suite-of-apis-and-comprehensive-reporting-dashboard-enables-digital-merchants-to-easily-comply-with-eu-regulatory-requirements-on-tax-calculation-evidence-collection-tax-return-creation-and-data-storage-
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
---