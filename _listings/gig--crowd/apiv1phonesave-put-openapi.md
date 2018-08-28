---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Put Phone Save
  version: 1.0.0
  description: Put phone save.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/gigme/phone/save:
    put:
      summary: Put Gigme Phone Save
      description: Put gigme phone save.
      operationId: putApiV1GigmePhoneSave
      x-api-path-slug: apiv1gigmephonesave-put
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: phoneNumber
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Phone
      - Save
  /api/v1/gigme/phone/send:
    post:
      summary: Post Gigme Phone Send
      description: Post gigme phone send.
      operationId: postApiV1GigmePhoneSend
      x-api-path-slug: apiv1gigmephonesend-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Phone
      - Send
  /api/v1/gigme/phone/confirm:
    post:
      summary: Post Gigme Phone Confirm
      description: Post gigme phone confirm.
      operationId: postApiV1GigmePhoneConfirm
      x-api-path-slug: apiv1gigmephoneconfirm-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Phone
      - Confirm
  /api/v1/phone/send:
    post:
      summary: Post Phone Send
      description: Post phone send.
      operationId: postApiV1PhoneSend
      x-api-path-slug: apiv1phonesend-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Phone
      - Send
  /api/v1/phone/confirm:
    post:
      summary: Post Phone Confirm
      description: Post phone confirm.
      operationId: postApiV1PhoneConfirm
      x-api-path-slug: apiv1phoneconfirm-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Phone
      - Confirm
  /api/v1/phone/save:
    put:
      summary: Put Phone Save
      description: Put phone save.
      operationId: putApiV1PhoneSave
      x-api-path-slug: apiv1phonesave-put
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: phoneNumber
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Phone
      - Save
  /api/v1/phone/check/{smsId}:
    get:
      summary: Get Phone Check Smsid
      description: Get phone check smsid.
      operationId: getApiV1PhoneCheckSms
      x-api-path-slug: apiv1phonechecksmsid-get
      parameters:
      - in: path
        name: smsId
      responses:
        200:
          description: OK
      tags:
      - Phone
      - Check
      - Smsid
  /api/v1/admin/user/emailAndPhone/{userId}:
    post:
      summary: Post Admin User Emailandphone Userid
      description: Post admin user emailandphone userid.
      operationId: postApiV1AdminUserEmailandphoneUser
      x-api-path-slug: apiv1adminuseremailandphoneuserid-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - User
      - Emailandphone
      - Userid
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