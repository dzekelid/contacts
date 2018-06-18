---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting X-related-model Contacts Contact
  description: X-related-model contacts contact.
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ContactGroups/{ContactGroupID}/Contacts:
    delete:
      summary: Delete Contact Groups Contacts
      description: Delete contactgroups contactgroup contacts.
      operationId: deleteContactgroupsContactgroupContacts
      x-api-path-slug: contactgroupscontactgroupidcontacts-delete
      parameters:
      - in: path
        name: ContactGroupID
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
    put:
      summary: Put Contact Groups Contacts
      description: Put contactgroups contactgroup contacts.
      operationId: putContactgroupsContactgroupContacts
      x-api-path-slug: contactgroupscontactgroupidcontacts-put
      parameters:
      - in: path
        name: ContactGroupID
      - in: body
        name: Contacts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
    x-related-model:
      summary: X-related-model Contact Groups Contacts
      description: X-related-model contactgroups contactgroup contacts.
      operationId: x-related-modelContactgroupsContactgroupContacts
      x-api-path-slug: contactgroupscontactgroupidcontacts-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
  /ContactGroups/{ContactGroupID}/Contacts/{ContactID}:
    delete:
      summary: Delete Contact Groups Contacts Contact
      description: Delete contactgroups contactgroup contacts contact.
      operationId: deleteContactgroupsContactgroupContactsContact
      x-api-path-slug: contactgroupscontactgroupidcontactscontactid-delete
      parameters:
      - in: path
        name: ContactGroupID
      - in: path
        name: ContactID
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
      - ContactID
    x-related-model:
      summary: X-related-model Contact Groups Contacts Contact
      description: X-related-model contactgroups contactgroup contacts contact.
      operationId: x-related-modelContactgroupsContactgroupContactsContact
      x-api-path-slug: contactgroupscontactgroupidcontactscontactid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - ContactGroups
      - ContactGroupID
      - Contacts
      - ContactID
  /Contacts:
    get:
      summary: Get Contacts
      description: Get contacts.
      operationId: getContacts
      x-api-path-slug: contacts-get
      parameters:
      - in: query
        name: IDs
        description: Filter by a comma-separated list of ContactIDs
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Contacts
    post:
      summary: Post Contacts
      description: Post contacts.
      operationId: postContacts
      x-api-path-slug: contacts-post
      parameters:
      - in: body
        name: Contacts
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Contacts
    put:
      summary: Put Contacts
      description: Put contacts.
      operationId: putContacts
      x-api-path-slug: contacts-put
      parameters:
      - in: body
        name: Contacts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
    x-related-model:
      summary: X-related-model Contacts
      description: X-related-model contacts.
      operationId: x-related-modelContacts
      x-api-path-slug: contacts-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Contacts
  /Contacts/{ContactID}:
    get:
      summary: Get Contacts Contact
      description: Get contacts contact.
      operationId: getContactsContact
      x-api-path-slug: contactscontactid-get
      parameters:
      - in: path
        name: ContactID
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
    post:
      summary: Post Contacts Contact
      description: Post contacts contact.
      operationId: postContactsContact
      x-api-path-slug: contactscontactid-post
      parameters:
      - in: path
        name: ContactID
      - in: body
        name: Contacts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
    x-related-model:
      summary: X-related-model Contacts Contact
      description: X-related-model contacts contact.
      operationId: x-related-modelContactsContact
      x-api-path-slug: contactscontactid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - ContactID
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