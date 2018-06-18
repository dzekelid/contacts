---
swagger: "2.0"
x-collection-name: Constant Contact
x-complete: 1
info:
  title: Constant Contact
  description: make-constant-contacts-leading-email-and-event-marketing-services-accessible-directly-from-your-app-
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
---