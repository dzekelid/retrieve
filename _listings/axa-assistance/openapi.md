---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 1
info:
  title: AXA Assistance
  description: axa-assistance-is-a-worldwide-specialist-for-car-insurance-travel-health-and-home-services--trust-in-axa-assistance-for-your-insurance
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /information/v1/countries:
    get:
      summary: Retrieve all countries
      description: Retrieve all countries
      operationId: getInformationV1Countries
      x-api-path-slug: informationv1countries-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - all
      - countries
  /information/v1/countries/alerts:
    get:
      summary: Retrieve the latest alerts worldwide
      description: Retrieve the latest alerts worldwide
      operationId: getInformationV1CountriesAlerts
      x-api-path-slug: informationv1countriesalerts-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - the
      - latest
      - alertAssistance
      - worldwide
  /information/v1/countries/{country_id}:
    get:
      summary: Retrieve a country detail
      description: Retrieve a country detail
      operationId: getInformationV1CountriesCountry_id
      x-api-path-slug: informationv1countriescountry-id-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrievecountry
      - detail
  /ondemand/v1/medical_providers/kinds:
    get:
      summary: 'Retrieve all medical provider kinds available for search (Ex: pharmacy,
        hospital ...)'
      description: 'Retrieve all medical provider kinds available for search (Ex:
        pharmacy, hospital ...)'
      operationId: getOndemandV1Medical_providersKinds
      x-api-path-slug: ondemandv1medical-providerskinds-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - all
      - medical
      - provider
      - kindAssistance
      - availablesearch
      - '(Ex:'
      - pharmacy
      - ""
      - hospital
      - '...)'
  /ondemand/v1/medical_providers/specialities:
    get:
      summary: 'Retrieve all medical provider specialities available for search (Ex:
        cardiology, dentist ...)'
      description: 'Retrieve all medical provider specialities available for search
        (Ex: cardiology, dentist ...)'
      operationId: getOndemandV1Medical_providersSpecialities
      x-api-path-slug: ondemandv1medical-providersspecialities-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - all
      - medical
      - provider
      - specialitieAssistance
      - availablesearch
      - '(Ex:'
      - cardiology
      - ""
      - dentist
      - '...)'
  /information/v1/countries/{country_id}/security_cards:
    get:
      summary: Retrieve security information for a country
      description: Retrieve security information for a country
      operationId: getInformationV1CountriesCountry_idSecurity_cards
      x-api-path-slug: informationv1countriescountry-idsecurity-cards-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - security
      - informationa
      - country
  /information/v1/countries/{country_id}/health_cards:
    get:
      summary: Retrieve health information for a country
      description: Retrieve health information for a country
      operationId: getInformationV1CountriesCountry_idHealth_cards
      x-api-path-slug: informationv1countriescountry-idhealth-cards-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - health
      - informationa
      - country
  /information/v1/countries/{country_id}/alerts:
    get:
      summary: Retrieve the latest alerts for a specified country
      description: Retrieve the latest alerts for a specified country
      operationId: getInformationV1CountriesCountry_idAlerts
      x-api-path-slug: informationv1countriescountry-idalerts-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - the
      - latest
      - alertsa
      - specified
      - country
  /service/v1/medical_consultations/{medical_consultation_id}/prescriptions/{prescription_id}/attachments/{attachment_id}:
    get:
      summary: Retrieve an attachment
      description: Retrieve an attachment
      operationId: getServiceV1Medical_consultationsMedical_consultation_idPrescriptionsPrescription_idAttachmentsAttac
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-idprescriptionsprescription-idattachmentsattachment-id-get
      parameters:
      - in: path
        name: attachment_id
        description: ID of the attachment
      - in: path
        name: medical_consultation_id
        description: ID of the medical consultation
      - in: path
        name: prescription_id
        description: ID of the prescription
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieveattachment
---