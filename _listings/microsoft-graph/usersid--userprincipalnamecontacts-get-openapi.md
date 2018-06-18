---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph List Contacts
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user (.../me/contacts), or from the specified contact
        folder.
      operationId: ListContacts
      x-api-path-slug: mecontacts-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
  /users/{id | userPrincipalName}/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user (.../me/contacts), or from the specified contact
        folder.
      operationId: ListContacts
      x-api-path-slug: usersid--userprincipalnamecontacts-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
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