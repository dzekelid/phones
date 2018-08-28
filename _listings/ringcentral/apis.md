---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Phones
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get Extension Phone Number List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
  description: "Returns the list of phone numbers that are used by a particular extension,
    and can be filtered by the phone number type. The returned list contains all numbers
    which are directly mapped to a given extension plus the features and also company-level
    numbers which may be used when performing different operations on behalf of this
    extension.\nApp Permission\nReadAccounts\nUser Permission\nReadUserPhoneNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [usageType] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get All Company Phone Numbers
  x-api-slug: restapiv1-0accountaccountidphonenumber-get
  description: "Returns the list of phone numbers assigned to RingCentral customer
    account. Both company-level and extension-level numbers are returned.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nHeavy\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Phone Number
  x-api-slug: restapiv1-0accountaccountidphonenumberphonenumberid-get
  description: "Returns the phone number(s) belonging to a certain account or extension
    by phoneNumberId(s). Batch request is supported.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nLight\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumberphonenumberid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Parse Phone Number [Beta]
  x-api-slug: restapiv1-0numberparserparse-post
  description: "Returns one or more parsed and/or formatted phone numbers that are
    passed as a string.\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n
    \  Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [nationalAsPriority]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0numberparserparse-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Phone Number List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
  description: "Returns the list of phone numbers that are used by a particular extension,
    and can be filtered by the phone number type. The returned list contains all numbers
    which are directly mapped to a given extension plus the features and also company-level
    numbers which may be used when performing different operations on behalf of this
    extension.\nApp Permission\nReadAccounts\nUser Permission\nReadUserPhoneNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [usageType] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get All Company Phone Numbers
  x-api-slug: restapiv1-0accountaccountidphonenumber-get
  description: "Returns the list of phone numbers assigned to RingCentral customer
    account. Both company-level and extension-level numbers are returned.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nHeavy\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Phone Number
  x-api-slug: restapiv1-0accountaccountidphonenumberphonenumberid-get
  description: "Returns the phone number(s) belonging to a certain account or extension
    by phoneNumberId(s). Batch request is supported.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nLight\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumberphonenumberid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Parse Phone Number [Beta]
  x-api-slug: restapiv1-0numberparserparse-post
  description: "Returns one or more parsed and/or formatted phone numbers that are
    passed as a string.\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n
    \  Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [nationalAsPriority]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0numberparserparse-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Parse Phone Number [Beta]
  x-api-slug: restapiv1-0numberparserparse-post
  description: "Returns one or more parsed and/or formatted phone numbers that are
    passed as a string.\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n
    \  Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [nationalAsPriority]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0numberparserparse-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Parse Phone Number [Beta]
  x-api-slug: restapiv1-0numberparserparse-post
  description: "Returns one or more parsed and/or formatted phone numbers that are
    passed as a string.\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n
    \  Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [nationalAsPriority]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0numberparserparse-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Phone Number
  x-api-slug: restapiv1-0accountaccountidphonenumberphonenumberid-get
  description: "Returns the phone number(s) belonging to a certain account or extension
    by phoneNumberId(s). Batch request is supported.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nLight\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumberphonenumberid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Phone Number
  x-api-slug: restapiv1-0accountaccountidphonenumberphonenumberid-get
  description: "Returns the phone number(s) belonging to a certain account or extension
    by phoneNumberId(s). Batch request is supported.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nLight\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumberphonenumberid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Phone Number
  x-api-slug: restapiv1-0accountaccountidphonenumberphonenumberid-get
  description: "Returns the phone number(s) belonging to a certain account or extension
    by phoneNumberId(s). Batch request is supported.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nLight\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumberphonenumberid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get All Company Phone Numbers
  x-api-slug: restapiv1-0accountaccountidphonenumber-get
  description: "Returns the list of phone numbers assigned to RingCentral customer
    account. Both company-level and extension-level numbers are returned.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nHeavy\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get All Company Phone Numbers
  x-api-slug: restapiv1-0accountaccountidphonenumber-get
  description: "Returns the list of phone numbers assigned to RingCentral customer
    account. Both company-level and extension-level numbers are returned.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nHeavy\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Phone Number List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
  description: "Returns the list of phone numbers that are used by a particular extension,
    and can be filtered by the phone number type. The returned list contains all numbers
    which are directly mapped to a given extension plus the features and also company-level
    numbers which may be used when performing different operations on behalf of this
    extension.\nApp Permission\nReadAccounts\nUser Permission\nReadUserPhoneNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [usageType] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Phone Number List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
  description: "Returns the list of phone numbers that are used by a particular extension,
    and can be filtered by the phone number type. The returned list contains all numbers
    which are directly mapped to a given extension plus the features and also company-level
    numbers which may be used when performing different operations on behalf of this
    extension.\nApp Permission\nReadAccounts\nUser Permission\nReadUserPhoneNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [usageType] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/phones/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidphonenumber-get-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---