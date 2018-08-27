---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Contact(s) by ID
  description: "Returns contact(s) by ID(s). Batch request is supported.\nApp Permission\nReadContacts\nUser
    Permission\nReadPersonalContacts\nUsage Plan Group\nHeavy\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadContacts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
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
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/address-book/contact:
    get:
      summary: Get Contacts
      description: "Returns user personal contacts.\nApp Permission\nReadContacts\nUser
        Permission\nReadPersonalContacts\nUsage Plan Group\nHeavy\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint,
        application needs to have [ReadContacts] permission\n\n\n404\nCMN-102\nResource
        for parameter [accountId] is not found"
      operationId: listContacts
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontact-get
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
        name: phoneNumber
      - in: query
        name: sortBy
        description: Sorts results by the specified property
      - in: query
        name: startsWith
        description: If specified, only contacts whose First name or Last name start
          with the mentioned substring are returned
      responses:
        200:
          description: OK
      tags:
      - Contacts
    post:
      summary: Create Contact
      description: "Creates personal user contact.\nApp Permission\nContacts\nUser
        Permission\nEditPersonalContacts\nUsage Plan Group\nHeavy\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [notes] value is invalid\n\n\n400\nPAB-102\nParameter [assistantPhone] is
        invalid. Failed to parse phone number.\n\n\n400\nPAB-103\nParameter [assistantPhone]
        is invalid. The phone number is too long.\n\n\n400\nPAB-104\nParameter [assistantPhone]
        is invalid. The phone numbers starting with the asterisk are not supported.\n\n\n400\nPAB-105\nParameter
        [assistantPhone] is invalid. The extensions longer than 10 digits are not
        supported.\n\n\n400\nPAB-106\nParameter [assistantPhone] is invalid. The DTMF
        sequences longer than 64 digits are not supported.\n\n\n403\nCMN-401\nIn order
        to call this API endpoint, application needs to have [Contacts] permission\n\n\n403\nCMN-408\nIn
        order to call this API endpoint, user needs to have [EditPersonalContacts]
        permission for requested resource.\n\n\n404\nCMN-102\nResource for parameter
        [accountId] is not found"
      operationId: createContact
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontact-post
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dialingPlan
        description: A country code value complying with the [ISO 3166-1 alpha-2](https://ru
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Contact
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/favorite:
    get:
      summary: Get Favorite Contacts
      description: "Returns favorite contacts of the current extension. Favorite contacts
        include both company contacts (extensions) and personal contacts (address
        book records).\nApp Permission\nReadContacts\nUser Permission\nReadPersonalContacts\nUsage
        Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n403\nCMN-401\nIn order to call this API endpoint, application
        needs to have [ReadContacts] permission\n\n\n403\nCMN-408\nIn order to call
        this API endpoint, user needs to have [ReadPersonalContacts] permission for
        requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
        is not found"
      operationId: listFavoriteContacts
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidfavorite-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Favorite
      - Contacts
    put:
      summary: Update Favorite Contacts
      description: "Updates favorite contacts of the current extension. Favorite contacts
        include both company contacts (extensions) and personal contacts (address
        book records).**Please note**: currently personal address book size is limited
        to 10 000 contacts.\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
        Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nCMN-101\nParameter [records.extensionId] value is
        invalid\n\n\n400\nFAV-100\nContact not found\n\n\n400\nFAV-101\nMore than
        one contact with the same [records.extensionId]\n\n\n400\nFAV-102\n[records.extensionId]
        and [records.contactId] could not be specified for one contact simultaneously\n\n\n400\nFAV-103\nMore
        than one contact with the same [records.id]\n\n\n400\nFAV-104\nContact limit
        exceeded\n\n\n400\nFAV-105\nContact not found in federated directory\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [Contacts] permission\n\n\n404\nCMN-102\nResource
        for parameter [accountId] is not found"
      operationId: updateFavoriteContacts
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidfavorite-put
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Favorite
      - Contacts
  /restapi/v1.0/account/{accountId}/directory/contacts:
    get:
      summary: Get Corporate Directory Contacts
      description: |-
        Returns contact information on corporate users of federated accounts. Please note: 1. User, DigitalUser, VirtualUser and FaxUser types are returned as User type. 2.ApplicationExtension type is not returned. 3. Only extensions in Enabled, Disabled and NotActivated state are returned.
        App Permission
        ReadAccounts
        Usage Plan Group
        Medium
      operationId: listDirectoryContacts
      x-api-path-slug: restapiv1-0accountaccountiddirectorycontacts-get
      parameters:
      - in: path
        name: accountId
        description: accountId
      - in: query
        name: excludeFederatedContacts
        description: excludeFederatedContacts
      - in: header
        name: If-None-Match
        description: If-None-Match
      - in: query
        name: page
        description: page
      - in: query
        name: perPage
        description: perPage
      - in: query
        name: siteId
        description: Internal identifier of the business site to which extensions
          belongs
      - in: query
        name: type
        description: Type of an extension
      responses:
        200:
          description: OK
      tags:
      - Corporate
      - Directory
      - Contacts
  /restapi/v1.0/account/{accountId}/directory/contacts/{contactId}:
    get:
      summary: Get Corporate Directory Contact
      description: |-
        Returns contact information on a particular corporate user of a federated account.
        App Permission
        ReadAccounts
        Usage Plan Group
        Medium
      operationId: loadDirectoryContact
      x-api-path-slug: restapiv1-0accountaccountiddirectorycontactscontactid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of owning account
      - in: path
        name: contactId
        description: Internal identifier of extension to read information for
      responses:
        200:
          description: OK
      tags:
      - Corporate
      - Directory
      - Contact
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/address-book/contact/{contactId}:
    get:
      summary: Get Contact(s) by ID
      description: "Returns contact(s) by ID(s). Batch request is supported.\nApp
        Permission\nReadContacts\nUser Permission\nReadPersonalContacts\nUsage Plan
        Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n403\nCMN-401\nIn order to call this API endpoint, application
        needs to have [ReadContacts] permission\n\n\n404\nCMN-102\nResource for parameter
        [extensionId] is not found"
      operationId: loadContact
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidaddressbookcontactcontactid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: contactId
        description: Internal identifier of a contact record in the RingCentral database
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Contact(s)
      - By
      - ID
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