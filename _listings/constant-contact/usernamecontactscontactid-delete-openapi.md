---
swagger: "2.0"
x-collection-name: Constant Contact
x-complete: 0
info:
  title: Constant Contact Opting-out Contact
  description: Opting-out Contact
  version: 1.0.0
host: api.constantcontact.com
basePath: /ws/customers/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{username}/contacts:
    get:
      summary: List Contacts
      description: List Contacts
      operationId: list-contacts
      x-api-path-slug: usernamecontacts-get
      parameters:
      - in: query
        name: listid
        description: Specific list
      - in: query
        name: updatedsince
        description: Specified date
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
    post:
      summary: Add Contact
      description: Add Contact
      operationId: add-contact
      x-api-path-slug: usernamecontacts-post
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Contact
  /{username}/lists/{list-id}/members:
    get:
      summary: Get Contacts Collection from a List
      description: Get Contacts Collection from a List
      operationId: get-contacts-collection-from-a-list
      x-api-path-slug: usernamelistslistidmembers-get
      parameters:
      - in: path
        name: list-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Collection
      - From
      - List
  /{username}/contacts/{contact-id}:
    delete:
      summary: Opting-out Contact
      description: Opting-out Contact
      operationId: optingout-contact
      x-api-path-slug: usernamecontactscontactid-delete
      parameters:
      - in: path
        name: contact-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Opting-out
      - Contact
    get:
      summary: Get Contact
      description: Get Contact
      operationId: get-contact
      x-api-path-slug: usernamecontactscontactid-get
      parameters:
      - in: path
        name: contact-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Contact
    put:
      summary: Update Contact
      description: Update Contact
      operationId: update-contact
      x-api-path-slug: usernamecontactscontactid-put
      parameters:
      - in: path
        name: contact-id
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Contact
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