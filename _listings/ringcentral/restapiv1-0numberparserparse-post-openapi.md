---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Parse Phone Number [Beta]
  description: "Returns one or more parsed and/or formatted phone numbers that are
    passed as a string.\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n
    \  Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [nationalAsPriority]
    value is invalid"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/phone-number:
    get:
      summary: Get Extension Phone Number List
      description: "Returns the list of phone numbers that are used by a particular
        extension, and can be filtered by the phone number type. The returned list
        contains all numbers which are directly mapped to a given extension plus the
        features and also company-level numbers which may be used when performing
        different operations on behalf of this extension.\nApp Permission\nReadAccounts\nUser
        Permission\nReadUserPhoneNumbers\nUsage Plan Group\nLight\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [usageType] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint,
        application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
        for parameter [extensionId] is not found"
      operationId: listExtensionPhoneNumbers
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: usageType
        description: Usage type of a phone number
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Phone
      - Number
      - List
  /restapi/v1.0/account/{accountId}/phone-number:
    get:
      summary: Get All Company Phone Numbers
      description: "Returns the list of phone numbers assigned to RingCentral customer
        account. Both company-level and extension-level numbers are returned.\nApp
        Permission\nReadAccounts\nUser Permission\nReadCompanyPhoneNumbers\nUsage
        Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nCMN-101\nParameter [perPage] value is invalid\n\n\n401\nCMN-405\nLogin
        to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadAccounts]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
      operationId: listAccountPhoneNumbers
      x-api-path-slug: restapiv1-0accountaccountidphonenumber-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: usageType
        description: Usage type of a phone number
      responses:
        200:
          description: OK
      tags:
      - Company
      - Phone
      - Numbers
  /restapi/v1.0/account/{accountId}/phone-number/{phoneNumberId}:
    get:
      summary: Get Phone Number
      description: "Returns the phone number(s) belonging to a certain account or
        extension by phoneNumberId(s). Batch request is supported.\nApp Permission\nReadAccounts\nUser
        Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nLight\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadAccounts]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
      operationId: loadAccountPhoneNumber
      x-api-path-slug: restapiv1-0accountaccountidphonenumberphonenumberid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: phoneNumberId
        description: Internal identifier of a phone number
      responses:
        200:
          description: OK
      tags:
      - Phone
      - Number
  /restapi/v1.0/number-parser/parse:
    post:
      summary: Parse Phone Number [Beta]
      description: "Returns one or more parsed and/or formatted phone numbers that
        are passed as a string.\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
        Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [nationalAsPriority]
        value is invalid"
      operationId: parsePhoneNumber
      x-api-path-slug: restapiv1-0numberparserparse-post
      parameters:
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: homeCountry
        description: Internal identifier of a home country
      - in: query
        name: nationalAsPriority
        description: The default value is False
      responses:
        200:
          description: OK
      tags:
      - Parse
      - Phone
      - Number
      - '[Beta]'
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