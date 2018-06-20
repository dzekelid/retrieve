---
name: Square
x-slug: square
description: Square helps millions of sellers run their business- from secure credit
  card processing to point of sale solutions. Get paid faster with Square and sign
  up today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
x-kinRank: "9"
x-alexaRank: "2436"
tags: Retrieve
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/square/apis.md
specificationVersion: "0.14"
apis:
- name: Square Connect API BatchRetrieveCatalogObjects
  x-api-slug: square-connect-api
  description: |-
    Returns a set of objects based on the provided ID.
    Each [CatalogItem](#type-catalogitem) returned in the set includes all of its
    child information including: all of its
    [CatalogItemVariation](#type-catalogitemvariation) objects, references to
    its [CatalogModifierList](#type-catalogmodifierlist) objects, and the ids of
    any [CatalogTax](#type-catalogtax) objects that apply to it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/catalog/batch-retrieve
  tags: BatchRetrieveCatalogObjects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/square/v2catalogbatchretrieve-post-openapi.md
- name: Square Connect API RetrieveCatalogObject
  x-api-slug: square-connect-api
  description: |-
    Returns a single [CatalogItem](#type-catalogitem) as a
    [CatalogObject](#type-catalogobject) based on the provided ID. The returned
    object includes all of the relevant [CatalogItem](#type-catalogitem)
    information including: [CatalogItemVariation](#type-catalogitemvariation)
    children, references to its
    [CatalogModifierList](#type-catalogmodifierlist) objects, and the ids of
    any [CatalogTax](#type-catalogtax) objects that apply to it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/catalog/object/{object_id}
  tags: RetrieveCatalogObject
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/square/v2catalogobjectobject-id-get-openapi.md
- name: Square Connect API RetrieveCustomer
  x-api-slug: square-connect-api
  description: Returns details for a single customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}
  tags: RetrieveCustomer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/square/v2customerscustomer-id-get-openapi.md
- name: Square Connect API RetrieveTransaction
  x-api-slug: square-connect-api
  description: Retrieves details for a single transaction.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/locations/{location_id}/transactions/{transaction_id}
  tags: RetrieveTransaction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/square/v2locationslocation-idtransactionstransaction-id-get-openapi.md
- name: Square Connect API
  x-api-slug: square-connect-api
  description: Square helps millions of sellers run their business- from secure credit
    card processing to point of sale solutions. Get paid faster with Square and sign
    up today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com//
  tags: Retrieve
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retrieve/master/_listings/square/openapi.md
x-common:
- type: x-base
  url: https://connect.squareup.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/square
- type: x-crunchbase
  url: https://crunchbase.com/organization/square
- type: x-developer
  url: https://connect.squareup.com/
- type: x-email
  url: press@squareup.com
- type: x-email
  url: security@squareup.com
- type: x-email
  url: lawenforcement@squareup.com
- type: x-email
  url: redemption@squareup.com
- type: x-email
  url: privacy@squareup.com
- type: x-email
  url: community@squareup.com
- type: x-email
  url: noreply@messaging.squareup.com
- type: x-email
  url: ir@squareup.com
- type: x-email
  url: takedowns@squareup.com
- type: x-github
  url: https://github.com/square
- type: x-twitter
  url: https://twitter.com/Square
- type: x-website
  url: http://squareup.com
- type: x-website
  url: https://squareup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---