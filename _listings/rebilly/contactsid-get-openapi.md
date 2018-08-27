---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Retrieve a contact
  description: Retrieve a contact with specified identifier string
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contacts:
    get:
      summary: Retrieve a list of contacts
      description: Retrieve a list of contacts
      operationId: contacts.get
      x-api-path-slug: contacts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Contacts
    post:
      summary: Create a contact
      description: Create a contact
      operationId: contacts.post
      x-api-path-slug: contacts-post
      parameters:
      - in: body
        name: body
        description: Contact resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
  /contacts/{id}:
    delete:
      summary: Delete a contact
      description: Delete a contact with predefined identifier string
      operationId: contacts.id.delete
      x-api-path-slug: contactsid-delete
      responses:
        200:
          description: OK
      tags:
      - Contact
    get:
      summary: Retrieve a contact
      description: Retrieve a contact with specified identifier string
      operationId: contacts.id.get
      x-api-path-slug: contactsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Contact
    put:
      summary: Create or update a contact with predefined ID
      description: Create or update a contact with predefined identifier string
      operationId: contacts.id.put
      x-api-path-slug: contactsid-put
      parameters:
      - in: body
        name: body
        description: Contact resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Update
      - Contact
      - Predefined
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