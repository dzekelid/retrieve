---
swagger: "2.0"
x-collection-name: Square
x-complete: 1
info:
  title: Square Connect
  description: client-library-for-accessing-the-square-connect-apis
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/catalog/batch-retrieve:
    post:
      summary: BatchRetrieveCatalogObjects
      description: |-
        Returns a set of objects based on the provided ID.
        Each [CatalogItem](#type-catalogitem) returned in the set includes all of its
        child information including: all of its
        [CatalogItemVariation](#type-catalogitemvariation) objects, references to
        its [CatalogModifierList](#type-catalogmodifierlist) objects, and the ids of
        any [CatalogTax](#type-catalogtax) objects that apply to it.
      operationId: BatchRetrieveCatalogObjects
      x-api-path-slug: v2catalogbatchretrieve-post
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - BatchRetrieveCatalogObjects
  /v2/catalog/object/{object_id}:
    get:
      summary: RetrieveCatalogObject
      description: |-
        Returns a single [CatalogItem](#type-catalogitem) as a
        [CatalogObject](#type-catalogobject) based on the provided ID. The returned
        object includes all of the relevant [CatalogItem](#type-catalogitem)
        information including: [CatalogItemVariation](#type-catalogitemvariation)
        children, references to its
        [CatalogModifierList](#type-catalogmodifierlist) objects, and the ids of
        any [CatalogTax](#type-catalogtax) objects that apply to it.
      operationId: RetrieveCatalogObject
      x-api-path-slug: v2catalogobjectobject-id-get
      parameters:
      - in: query
        name: include_related_objects
        description: If `true`, the response will include additional objects that
          are related to therequested object, as follows:If the `object` field of
          the response contains a [CatalogItem](#type-catalogitem),its associated
          [CatalogCategory](#type-catalogcategory), [CatalogTax](#type-catalogtax)es,
          and[CatalogModifierList](#type-catalogmodifierlist)s will be returned in
          the `related_objects` field of theresponse
      - in: path
        name: object_id
        description: The object ID of any type of [CatalogObject](#type-catalogobject)s
          to be retrieved
      responses:
        200:
          description: OK
      tags:
      - RetrieveCatalogObject
  /v2/customers/{customer_id}:
    get:
      summary: RetrieveCustomer
      description: Returns details for a single customer.
      operationId: RetrieveCustomer
      x-api-path-slug: v2customerscustomer-id-get
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: path
        name: customer_id
        description: The ID of the customer to retrieve
      responses:
        200:
          description: OK
      tags:
      - RetrieveCustomer
  /v2/locations/{location_id}/transactions/{transaction_id}:
    get:
      summary: RetrieveTransaction
      description: Retrieves details for a single transaction.
      operationId: RetrieveTransaction
      x-api-path-slug: v2locationslocation-idtransactionstransaction-id-get
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: path
        name: location_id
        description: The ID of the transactions associated location
      - in: path
        name: transaction_id
        description: The ID of the transaction to retrieve
      responses:
        200:
          description: OK
      tags:
      - RetrieveTransaction
---