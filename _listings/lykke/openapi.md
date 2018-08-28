swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
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
  /api/CountryPhoneCodes:
    get:
      summary: Get API Countryphonecodes
      description: Get api countryphonecodes.
      operationId: ApiCountryPhoneCodesGet
      x-api-path-slug: apicountryphonecodes-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Countryphonecodes