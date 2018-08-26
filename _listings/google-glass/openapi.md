---
swagger: "2.0"
x-collection-name: Google Glass
x-complete: 1
info:
  title: Google Mirror
  description: interacts-with-glass-users-via-the-timeline-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /mirror/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contacts:
    get:
      summary: Get Contacts
      description: Retrieves a list of contacts for the authenticated user.
      operationId: mirror.contacts.list
      x-api-path-slug: contacts-get
      responses:
        200:
          description: OK
      tags:
      - Contact
    post:
      summary: Insert Contact
      description: Inserts a new contact.
      operationId: mirror.contacts.insert
      x-api-path-slug: contacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
  /contacts/{id}:
    delete:
      summary: Delete Contact
      description: Deletes a contact.
      operationId: mirror.contacts.delete
      x-api-path-slug: contactsid-delete
      parameters:
      - in: path
        name: id
        description: The ID of the contact
      responses:
        200:
          description: OK
      tags:
      - Contact
    get:
      summary: Get Contact
      description: Gets a single contact by ID.
      operationId: mirror.contacts.get
      x-api-path-slug: contactsid-get
      parameters:
      - in: path
        name: id
        description: The ID of the contact
      responses:
        200:
          description: OK
      tags:
      - Contact
    patch:
      summary: Update Contact
      description: Updates a contact in place. This method supports patch semantics.
      operationId: mirror.contacts.patch
      x-api-path-slug: contactsid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The ID of the contact
      responses:
        200:
          description: OK
      tags:
      - Contact
    put:
      summary: Update Contact
      description: Updates a contact in place.
      operationId: mirror.contacts.update
      x-api-path-slug: contactsid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The ID of the contact
      responses:
        200:
          description: OK
      tags:
      - Contact
---