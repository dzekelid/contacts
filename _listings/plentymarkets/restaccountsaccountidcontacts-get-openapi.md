---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List contacts
  description: Lists contacts of the account. The ID of the account must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/contacts:
    get:
      summary: List contacts
      description: List contacts.
      operationId: getRestAccountsContacts
      x-api-path-slug: restaccountscontacts-get
      parameters:
      - in: query
        name: billingAddressId
        description: Filter that restricts the search result to contacts with a billing
          address with the id provided
      - in: query
        name: contactAddress
        description: Filter that restricts the search result to contacts with a specific
          address
      - in: query
        name: contactEmail
        description: Filter that restricts the search result to contacts resembling
          to the given email address
      - in: query
        name: contactId
        description: Filter that restricts the search result to a specific contact
      - in: query
        name: countryId
        description: Filter that restricts the search result to contacts with a specific
          country
      - in: query
        name: createdAtAfter
        description: Filter that restricts the search result to contacts that were
          created after a specific date
      - in: query
        name: createdAtBefore
        description: Filter that restricts the search result to contacts that were
          created before a specific date
      - in: query
        name: deliveryAddressId
        description: Filter that restricts the search result to contacts with a delivery
          address with the id provided
      - in: query
        name: email
        description: Filter that restricts the search result to contacts with a specific
          email address
      - in: query
        name: externalId
        description: Filter that restricts the search result to contacts with a specific
          externalId
      - in: query
        name: fullText
        description: Filter for a fulltext search
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: name
        description: Filter that restricts the search result to contacts with a specific
          name
      - in: query
        name: newsletterAllowance
        description: Filter that restricts the search result to contacts who registered
          for the newsletter
      - in: query
        name: newsletterAllowanceAfter
        description: Filter that restricts the search result to contacts who registered
          for the newsletter after a specific date
      - in: query
        name: newsletterAllowanceBefore
        description: Filter that restricts the search result to contacts who registered
          for the newsletter before a specific date
      - in: query
        name: number
        description: Filter that restricts the search result to contacts with a specific
          number
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: plentyId
        description: Filter that restricts the search result to contacts with a specific
          plentyId
      - in: query
        name: postalCode
        description: Filter that restricts the search result to contacts with a specific
          postal code
      - in: query
        name: privatePhone
        description: Filter that restricts the search result to contacts with a private
          phone number
      - in: query
        name: referrerId
        description: Filter that restricts the search result to contacts with a specific
          referrer
      - in: query
        name: town
        description: Filter that restricts the search result to contacts with a specific
          town
      - in: query
        name: typeId
        description: Filter that restricts the search result to contacts with a specific
          contact type
      - in: query
        name: updatedAtAfter
        description: Filter that restricts the search result to contacts that were
          updated after a specific date
      - in: query
        name: updatedAtBefore
        description: Filter that restricts the search result to contacts that were
          updated before a specific date
      - in: query
        name: userId
        description: Filter that restricts the search result to contacts with a specific
          user
      - in: query
        name: with
        description: Includes the specified contact information in the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
  /rest/accounts/contacts/{contactId}/addresses/{addressTypeId?}:
    get:
      summary: List addresses that are linked with contacts
      description: Lists addresses of the contact. The ID of the contact must be specified.
      operationId: getRestAccountsContactsContactAddressesAddresstype
      x-api-path-slug: restaccountscontactscontactidaddressesaddresstypeid-get
      parameters:
      - in: path
        name: addressTypeId?
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - List
      - Addresses
      - That
      - Are
      - Linked
      - Contacts
  /rest/accounts/{accountId}/contacts:
    get:
      summary: List contacts
      description: Lists contacts of the account. The ID of the account must be specified.
      operationId: getRestAccountsAccountContacts
      x-api-path-slug: restaccountsaccountidcontacts-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
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