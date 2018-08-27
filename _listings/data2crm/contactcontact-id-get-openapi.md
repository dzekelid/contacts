---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 0
info:
  title: Data2CRM GET for Contact
  description: Return contact information
  version: "1"
host: api.data2crm.com:80
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contact:
    get:
      summary: GET for Contact
      description: Returns all contacts from the system
      operationId: getContactCollection
      x-api-path-slug: contact-get
      parameters:
      - in: query
        name: filter
        description: Filter
      - in: query
        name: limit
        description: 'Amount of results (default: 25)'
      - in: query
        name: offset
        description: 'Start from record (default: 0)'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-DATA-ENABLE
        description: Data Enable
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Contacts
    post:
      summary: POST for Contact
      description: Add contact into the system
      operationId: createContactEntity
      x-api-path-slug: contact-post
      parameters:
      - in: body
        name: body
        description: Add contact into the system
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Contacts
  /contact/count:
    get:
      summary: COUNT for Contact
      description: Count all contacts from the system
      operationId: getContactCountCollection
      x-api-path-slug: contactcount-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Count
  /contact/describe:
    get:
      summary: DESCRIBE for Contact
      description: Returns describe for contacts
      operationId: getContactDescribe
      x-api-path-slug: contactdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Describe
  /contact/{contact_id}:
    delete:
      summary: DELETE for Contact
      description: Delete contact information
      operationId: deleteContactEntity
      x-api-path-slug: contactcontact-id-delete
      parameters:
      - in: path
        name: contact_id
        description: Contact Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Contacts
    get:
      summary: GET for Contact
      description: Return contact information
      operationId: getContactEntity
      x-api-path-slug: contactcontact-id-get
      parameters:
      - in: path
        name: contact_id
        description: Contact Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
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