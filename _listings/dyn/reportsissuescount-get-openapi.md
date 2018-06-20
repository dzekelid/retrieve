---
swagger: "2.0"
x-collection-name: Dyn
x-complete: 0
info:
  title: Dyn Retrieve Count of Email Issues
  version: 1.0.0
  description: Retrieving a total count of Email issues
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
  reports/bounces:
    get:
      summary: Retrieve Email Bounces
      description: Retrieving the Email SPAM Complaints
      operationId: getReportsBounces
      x-api-path-slug: reportsbounces-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: bounce_code - Indicates the code associated with the bounced Email.
      - in: query
        name: bounce_code_id - The numeric code determined by the bounce processor.
      - in: query
        name: bounce_rule - Indicates the rule that caused this email to bounce.
      - in: query
        name: bounce_type
        description: Type of bounce for filtering
      - in: query
        name: bounce_type_id - Indicates whether the bounce type is a hard or soft
          bounce.nValid Values:n1 - Hard Bouncen2 - Soft Bounce
      - in: query
        name: emailaddress
        description: Email address of recipient for filtering
      - in: query
        name: endtime
        description: Required
      - in: query
        name: noheaders
        description: Determines whether or not headers are included in the response
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: sender_id
        description: Identifying number of the sender
      - in: query
        name: startindex
        description: Number indicating where to begin reporting results
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Email
      - Bounces
  reports/bounces/count:
    get:
      summary: Retrieve Count of Email Bounces
      description: Retrieving a total count of Email bounces using the API requires
        specific syntax for the REST API.
      operationId: getReportsBouncesCount
      x-api-path-slug: reportsbouncescount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - Bounces
  reports/clicks/count:
    get:
      summary: Retrieve Count of Email Links Clicked
      description: Retrieving a total of Email links clicked
      operationId: getReportsClicksCount
      x-api-path-slug: reportsclickscount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: domainu00a0
        description: Domain of the recipient, such as &#8220;gmail
      - in: query
        name: emailaddress
        description: Email address of recipient for filteringu0010
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filteringu0010
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - Links
      - Clicked
  reports/clicks/count/unique:
    get:
      summary: Retrieve Count of Email Links Clicked
      description: Retrieving a total of Email links clicked
      operationId: getReportsClicksCountUnique
      x-api-path-slug: reportsclickscountunique-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: domainu00a0
        description: Domain of the recipient, such as &#8220;gmail
      - in: query
        name: emailaddress
        description: Email address of recipient for filteringu0010
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filteringu0010
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - Links
      - Clicked
  reports/complaints:
    get:
      summary: Retrieve Email SPAM Complaints
      description: Retrieve Email SPAM Complaints
      operationId: getReportsComplaints
      x-api-path-slug: reportscomplaints-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: startindex
        description: Number indicating where to begin reporting results
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Email
      - SPAM
      - Complaints
  reports/complaints/count:
    get:
      summary: Retrieve Count of Email SPAM Complaints
      description: Retrieving a total count of Email complaints
      operationId: getReportsComplaintsCount
      x-api-path-slug: reportscomplaintscount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: endtime
        description: Required
      - in: query
        name: starttime
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - SPAM
      - Complaints
  reports/delivered:
    get:
      summary: Retrieve Emails Delivered
      description: Retrieve Emails Delivered
      operationId: getReportsDelivered
      x-api-path-slug: reportsdelivered-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: startindex
        description: Number indicating where to begin reporting results
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Emails
      - Delivered
  reports/delivered/count:
    get:
      summary: Retrieve Count of Emails Delivered
      description: Retrieve Count of Emails Delivered
      operationId: getReportsDeliveredCount
      x-api-path-slug: reportsdeliveredcount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Emails
      - Delivered
  reports/issues:
    get:
      summary: Retrieve Email Issues
      description: Retrieve Email Issues
      operationId: getReportsIssues
      x-api-path-slug: reportsissues-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: emailaddress
        description: Email address of recipient for filtering
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: sender_id
        description: Identifying number of the sender
      - in: query
        name: startindex
        description: Number indicating where to begin reporting results
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Email
      - Issues
  reports/issues/count:
    get:
      summary: Retrieve Count of Email Issues
      description: Retrieving a total count of Email issues
      operationId: getReportsIssuesCount
      x-api-path-slug: reportsissuescount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: endtime
        description: Required
      - in: query
        name: starttime
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - Issues
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