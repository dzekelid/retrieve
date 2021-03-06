---
name: Dyn
x-slug: dyn
description: Dyn is home to the worlds most trusted DNS product suite and the worlds
  most reputable Email Deliverability Service.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
x-kinRank: "8"
x-alexaRank: "20789"
tags: Retrieve
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/apis.md
specificationVersion: "0.14"
apis:
- name: Dyn Retrieve email sub-accounts
  x-api-slug: dyn
  description: Retrieving a list of up to 25 Email Sub-Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////accounts
  tags: Retrieve,Email, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/accounts-get-openapi.md
- name: Dyn Retrieve Recipient(s) Status
  x-api-slug: dyn
  description: Retrieve Recipient(s) Status
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////recipients/status
  tags: Retrieve, Recipients, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/recipientsstatus-get-openapi.md
- name: Dyn Retrieve Email Bounces
  x-api-slug: dyn
  description: Retrieving the Email SPAM Complaints
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/bounces
  tags: Retrieve,Email, Bounces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsbounces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsbounces-get-openapi.md
- name: Dyn Retrieve Count of Email Bounces
  x-api-slug: dyn
  description: Retrieving a total count of Email bounces using the API requires specific
    syntax for the REST API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/bounces/count
  tags: Retrieve, Count, of,Email, Bounces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsbouncescount-get-openapi.md
- name: Dyn Retrieve Count of Email Links Clicked
  x-api-slug: dyn
  description: Retrieving a total of Email links clicked
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/clicks/count
  tags: Retrieve, Count, of,Email, Links, Clicked
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsclickscount-get-openapi.md
- name: Dyn Retrieve Count of Email Links Clicked
  x-api-slug: dyn
  description: Retrieving a total of Email links clicked
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/clicks/count/unique
  tags: Retrieve, Count, of,Email, Links, Clicked
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsclickscountunique-get-openapi.md
- name: Dyn Retrieve Email SPAM Complaints
  x-api-slug: dyn
  description: Retrieve Email SPAM Complaints
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/complaints
  tags: Retrieve,Email, SPAM, Complaints
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportscomplaints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportscomplaints-get-openapi.md
- name: Dyn Retrieve Count of Email SPAM Complaints
  x-api-slug: dyn
  description: Retrieving a total count of Email complaints
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/complaints/count
  tags: Retrieve, Count, of,Email, SPAM, Complaints
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportscomplaintscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportscomplaintscount-get-openapi.md
- name: Dyn Retrieve Emails Delivered
  x-api-slug: dyn
  description: Retrieve Emails Delivered
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/delivered
  tags: Retrieve,Emails, Delivered
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsdelivered-get-openapi.md
- name: Dyn Retrieve Count of Emails Delivered
  x-api-slug: dyn
  description: Retrieve Count of Emails Delivered
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/delivered/count
  tags: Retrieve, Count, of,Emails, Delivered
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsdeliveredcount-get-openapi.md
- name: Dyn Retrieve Email Issues
  x-api-slug: dyn
  description: Retrieve Email Issues
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/issues
  tags: Retrieve,Email, Issues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsissues-get-openapi.md
- name: Dyn Retrieve Count of Email Issues
  x-api-slug: dyn
  description: Retrieving a total count of Email issues
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/issues/count
  tags: Retrieve, Count, of,Email, Issues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsissuescount-get-openapi.md
- name: Dyn Retrieve Count of Email Opens
  x-api-slug: dyn
  description: Returns total number of unique opens for the specified account for
    the specified date range. Including a date range is highly recommended.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/opens/count/unique
  tags: Retrieve, Count, of,Email, Opens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsopenscountunique-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportsopenscountunique-get-openapi.md
- name: Dyn Retrieve Emails Sent
  x-api-slug: dyn
  description: Retrieve Emails Sent
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/sent
  tags: Retrieve,Emails, Sent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportssent-get-openapi.md
- name: Dyn Retrieve Count of Emails Sent
  x-api-slug: dyn
  description: Retrieve Count of Emails Sent
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/sent/count
  tags: Retrieve, Count, of,Emails, Sent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/reportssentcount-get-openapi.md
- name: Dyn Retrieve Suppression Email Addresses
  x-api-slug: dyn
  description: Retrieving a list of Email addresses on the suppression list
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////suppressions
  tags: Retrieve, Suppression,Email, resses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/suppressions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/suppressions-get-openapi.md
- name: Dyn Retrieve Suppression Count
  x-api-slug: dyn
  description: Retrieving the count of Email addresses on the suppression list
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////suppressions/count
  tags: Retrieve, Suppression, Count
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/suppressionscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/suppressionscount-get-openapi.md
- name: Dyn
  x-api-slug: dyn
  description: Dyn is home to the worlds most trusted DNS product suite and the worlds
    most reputable Email Deliverability Service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:///
  tags: Retrieve
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/dyn/openapi.md
x-common:
- type: x-base
  url: https://api.dynect.net
- type: x-blog
  url: http://research.dyn.com/
- type: x-blog
  url: http://dyn.com/blog/
- type: x-blog-rss
  url: http://feeds.feedburner.com/dyn-blog
- type: x-blog-rss
  url: http://research.dyn.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/dyn
- type: x-crunchbase
  url: https://crunchbase.com/organization/dyn
- type: x-developer
  url: https://help.dyn.com/developers/
- type: x-email
  url: billing@dyndns.com
- type: x-email
  url: privacy@dyn.com
- type: x-forum
  url: http://www.dyndnscommunity.com/
- type: x-getting-started
  url: http://dyn.com/product-wizard/
- type: x-github
  url: https://github.com/dyninc
- type: x-partners
  url: http://dyn.com/about/partners/
- type: x-php-sdk
  url: https://github.com/dyninc/dyn-php/
- type: x-privacy
  url: http://dyn.com/legal/dyn-privacy-policy/
- type: x-python-sdk
  url: https://github.com/dyninc/dyn-python/
- type: x-selfservice-registration
  url: https://account.dyn.com/entrance/
- type: x-status
  url: http://www.dynstatus.com/
- type: x-terms-of-service
  url: http://dyn.com/legal/dyn-services-agreement/
- type: x-twitter
  url: https://twitter.com/Dyn
- type: x-website
  url: http://dynect.net
- type: x-website
  url: http://dyn.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---