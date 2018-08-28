---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Clientphone
  version: 1.0.0
  description: Add api clientphone.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/Utils/isUSorCanadaNumber/{phoneNumber}:
    get:
      summary: Get API Utils Isusorcanadanumber Phonenumber
      description: Get api utils isusorcanadanumber phonenumber.
      operationId: ApiUtilsIsUSorCanadaNumberByPhoneNumberGet
      x-api-path-slug: apiutilsisusorcanadanumberphonenumber-get
      parameters:
      - in: path
        name: phoneNumber
      responses:
        200:
          description: OK
      tags:
      - Utils
      - Isusorcanadanumber
      - Phonenumber
  /api/CheckMobilePhone:
    get:
      summary: Get API Checkmobilephone
      description: Get api checkmobilephone.
      operationId: ApiCheckMobilePhoneGet
      x-api-path-slug: apicheckmobilephone-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: code
      - in: query
        name: phoneNumber
      responses:
        200:
          description: OK
      tags:
      - Checkmobilephone
    post:
      summary: Add API Checkmobilephone
      description: Add api checkmobilephone.
      operationId: ApiCheckMobilePhonePost
      x-api-path-slug: apicheckmobilephone-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: phoneModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Checkmobilephone
  /api/ClientPhone:
    post:
      summary: Add API Clientphone
      description: Add api clientphone.
      operationId: ApiClientPhonePost
      x-api-path-slug: apiclientphone-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: phoneModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clientphone
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