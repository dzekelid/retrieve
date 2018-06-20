---
swagger: "2.0"
x-collection-name: Dyn
x-complete: 0
info:
  title: Dyn Retrieve Recipient(s) Status
  version: 1.0.0
  description: Retrieve Recipient(s) Status
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  accounts:
    get:
      summary: Retrieve email sub-accounts
      description: Retrieving a list of up to 25 Email Sub-Accounts
      operationId: getAccounts
      x-api-path-slug: accounts-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: startindex
        description: An integer to indicate the starting index of where to begin the
          list of sub-accounts
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Email
      - Accounts
  recipients/status:
    get:
      summary: Retrieve Recipient(s) Status
      description: Retrieve Recipient(s) Status
      operationId: getRecipientsStatus
      x-api-path-slug: recipientsstatus-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: emailaddress
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Recipients
      - Status
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