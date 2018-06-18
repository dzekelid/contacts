---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /me/contactFolders/{id}/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user (.../me/contacts), or from the specified contact
        folder.
      operationId: ListContacts
      x-api-path-slug: mecontactfoldersidcontacts-get
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
      - in: path
        name: Id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
  /users/{id | userPrincipalName}/contactFolders/{id}/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user (.../me/contacts), or from the specified contact
        folder.
      operationId: ListContacts
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontacts-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
  /me/contactFolder/{id}/childFolders/{id}/.../contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user.
      operationId: ListContacts
      x-api-path-slug: mecontactfolderidchildfoldersid---contacts-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
  /users/{id | userPrincipalName}/contactFolders/{id}/childFolders/{id}/contacts:
    get:
      summary: List Contacts
      description: List contacts Get a contact collection from the default Contacts
        folder of the signed-in user.
      operationId: ListContacts
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontacts-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
---