swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/inboundlead/checkformatchinggroups:
    get:
      summary: Check for Matching groups for the given leads based on contact item
        values i.e. Emails and Phones.
      description: Check for matching groups for the given leads based on contact
        item values i.e. emails and phones..
      operationId: InboundLead_CheckForMatchingGroupsByleadIdBypageSizeBypageNumber
      x-api-path-slug: apiinboundleadcheckformatchinggroups-get
      parameters:
      - in: query
        name: leadId
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - CheckMatching
      - Groupsthe
      - Given
      - Leads
      - Based
      - "On"
      - Contact
      - Item
      - Values
      - I
      - E
      - ""
      - Emails
      - Phones
  /api/job/NormalisePhoneNumbers:
    post:
      summary: Normalises phone numbers for agency
      description: Normalises phone numbers for agency.
      operationId: Job_NormalisePhoneNumbersBynormalisePhoneNumbers
      x-api-path-slug: apijobnormalisephonenumbers-post
      parameters:
      - in: body
        name: normalisePhoneNumbers
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Normalises
      - Phone
      - Numbersagency
  /api/people/searchcontacts:
    post:
      summary: Search contacts based on the phone number provided
      description: Search contacts based on the phone number provided.
      operationId: People_SearchContactsBysearchCommandDataContract
      x-api-path-slug: apipeoplesearchcontacts-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: searchCommandDataContract
        description: Search data contract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Search
      - Contacts
      - Based
      - "On"
      - Phone
      - Number
      - Provided