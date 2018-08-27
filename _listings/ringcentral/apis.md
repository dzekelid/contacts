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
tags: Contacts
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get Contacts
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontact-get
  description: "Returns user personal contacts.\nApp Permission\nReadContacts\nUser
    Permission\nReadPersonalContacts\nUsage Plan Group\nHeavy\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadContacts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontact-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontact-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Favorite Contacts
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfavorite-get
  description: "Returns favorite contacts of the current extension. Favorite contacts
    include both company contacts (extensions) and personal contacts (address book
    records).\nApp Permission\nReadContacts\nUser Permission\nReadPersonalContacts\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadContacts] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadPersonalContacts] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfavorite-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfavorite-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Favorite Contacts
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfavorite-put
  description: "Updates favorite contacts of the current extension. Favorite contacts
    include both company contacts (extensions) and personal contacts (address book
    records).**Please note**: currently personal address book size is limited to 10
    000 contacts.\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [records.extensionId] value is invalid\n\n\n400\nFAV-100\nContact
    not found\n\n\n400\nFAV-101\nMore than one contact with the same [records.extensionId]\n\n\n400\nFAV-102\n[records.extensionId]
    and [records.contactId] could not be specified for one contact simultaneously\n\n\n400\nFAV-103\nMore
    than one contact with the same [records.id]\n\n\n400\nFAV-104\nContact limit exceeded\n\n\n400\nFAV-105\nContact
    not found in federated directory\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [Contacts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfavorite-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Corporate Directory Contacts
  x-api-slug: restapiv1-0accountaccountiddirectorycontacts-get
  description: |-
    Returns contact information on corporate users of federated accounts. Please note: 1. User, DigitalUser, VirtualUser and FaxUser types are returned as User type. 2.ApplicationExtension type is not returned. 3. Only extensions in Enabled, Disabled and NotActivated state are returned.
    App Permission
    ReadAccounts
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountiddirectorycontacts-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Contact
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post
  description: "Creates personal user contact.\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [notes] value is invalid\n\n\n400\nPAB-102\nParameter
    [assistantPhone] is invalid. Failed to parse phone number.\n\n\n400\nPAB-103\nParameter
    [assistantPhone] is invalid. The phone number is too long.\n\n\n400\nPAB-104\nParameter
    [assistantPhone] is invalid. The phone numbers starting with the asterisk are
    not supported.\n\n\n400\nPAB-105\nParameter [assistantPhone] is invalid. The extensions
    longer than 10 digits are not supported.\n\n\n400\nPAB-106\nParameter [assistantPhone]
    is invalid. The DTMF sequences longer than 64 digits are not supported.\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [Contacts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditPersonalContacts] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Corporate Directory Contact
  x-api-slug: restapiv1-0accountaccountiddirectorycontactscontactid-get
  description: |-
    Returns contact information on a particular corporate user of a federated account.
    App Permission
    ReadAccounts
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountiddirectorycontactscontactid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Contact(s) by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontactcontactid-get
  description: "Returns contact(s) by ID(s). Batch request is supported.\nApp Permission\nReadContacts\nUser
    Permission\nReadPersonalContacts\nUsage Plan Group\nHeavy\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadContacts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontactcontactid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Contact(s) by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontactcontactid-put
  description: "Updates personal contact information by contact ID(s). Batch request
    is supported\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [notes] value is invalid\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [Contacts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditPersonalContacts] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontactcontactid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Contact(s) by ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontactcontactid-delete
  description: "Deletes contact(s) by ID(s). Batch request is supported.\nApp Permission\nContacts\nUser
    Permission\nEditPersonalContacts\nUsage Plan Group\nHeavy\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [Contacts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditPersonalContacts] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [extensionId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontactcontactid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Contact
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post
  description: "Creates personal user contact.\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [notes] value is invalid\n\n\n400\nPAB-102\nParameter
    [assistantPhone] is invalid. Failed to parse phone number.\n\n\n400\nPAB-103\nParameter
    [assistantPhone] is invalid. The phone number is too long.\n\n\n400\nPAB-104\nParameter
    [assistantPhone] is invalid. The phone numbers starting with the asterisk are
    not supported.\n\n\n400\nPAB-105\nParameter [assistantPhone] is invalid. The extensions
    longer than 10 digits are not supported.\n\n\n400\nPAB-106\nParameter [assistantPhone]
    is invalid. The DTMF sequences longer than 64 digits are not supported.\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [Contacts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditPersonalContacts] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Corporate Directory Contact
  x-api-slug: restapiv1-0accountaccountiddirectorycontactscontactid-get
  description: |-
    Returns contact information on a particular corporate user of a federated account.
    App Permission
    ReadAccounts
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountiddirectorycontactscontactid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Corporate Directory Contact
  x-api-slug: restapiv1-0accountaccountiddirectorycontactscontactid-get
  description: |-
    Returns contact information on a particular corporate user of a federated account.
    App Permission
    ReadAccounts
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountiddirectorycontactscontactid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Corporate Directory Contact
  x-api-slug: restapiv1-0accountaccountiddirectorycontactscontactid-get
  description: |-
    Returns contact information on a particular corporate user of a federated account.
    App Permission
    ReadAccounts
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountiddirectorycontactscontactid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Contact
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post
  description: "Creates personal user contact.\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [notes] value is invalid\n\n\n400\nPAB-102\nParameter
    [assistantPhone] is invalid. Failed to parse phone number.\n\n\n400\nPAB-103\nParameter
    [assistantPhone] is invalid. The phone number is too long.\n\n\n400\nPAB-104\nParameter
    [assistantPhone] is invalid. The phone numbers starting with the asterisk are
    not supported.\n\n\n400\nPAB-105\nParameter [assistantPhone] is invalid. The extensions
    longer than 10 digits are not supported.\n\n\n400\nPAB-106\nParameter [assistantPhone]
    is invalid. The DTMF sequences longer than 64 digits are not supported.\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [Contacts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditPersonalContacts] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Contact
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post
  description: "Creates personal user contact.\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [notes] value is invalid\n\n\n400\nPAB-102\nParameter
    [assistantPhone] is invalid. Failed to parse phone number.\n\n\n400\nPAB-103\nParameter
    [assistantPhone] is invalid. The phone number is too long.\n\n\n400\nPAB-104\nParameter
    [assistantPhone] is invalid. The phone numbers starting with the asterisk are
    not supported.\n\n\n400\nPAB-105\nParameter [assistantPhone] is invalid. The extensions
    longer than 10 digits are not supported.\n\n\n400\nPAB-106\nParameter [assistantPhone]
    is invalid. The DTMF sequences longer than 64 digits are not supported.\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [Contacts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditPersonalContacts] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Contact
  x-api-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post
  description: "Creates personal user contact.\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
    Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [notes] value is invalid\n\n\n400\nPAB-102\nParameter
    [assistantPhone] is invalid. Failed to parse phone number.\n\n\n400\nPAB-103\nParameter
    [assistantPhone] is invalid. The phone number is too long.\n\n\n400\nPAB-104\nParameter
    [assistantPhone] is invalid. The phone numbers starting with the asterisk are
    not supported.\n\n\n400\nPAB-105\nParameter [assistantPhone] is invalid. The extensions
    longer than 10 digits are not supported.\n\n\n400\nPAB-106\nParameter [assistantPhone]
    is invalid. The DTMF sequences longer than 64 digits are not supported.\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [Contacts] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditPersonalContacts] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post-openapi.md
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