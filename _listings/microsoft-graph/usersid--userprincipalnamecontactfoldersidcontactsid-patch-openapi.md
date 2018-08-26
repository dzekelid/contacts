---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Update Contact
  description: Update contact Update the properties of a contact object.
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
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: mecontacts-post
      parameters:
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
      - Contact
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
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: usersid--userprincipalnamecontacts-post
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
      - Contact
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
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: mecontactfoldersidcontacts-post
      parameters:
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
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
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontacts-post
      parameters:
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
      - Contact
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
  /me/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: mecontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: mecontactsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: mecontactsid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
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
      - Contact
  /users/{id | userPrincipalName}/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: usersid--userprincipalnamecontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: usersid--userprincipalnamecontactsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: usersid--userprincipalnamecontactsid-patch
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
      - Contact
  /me/contactFolders/{id}/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: mecontactfoldersidcontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: mecontactfoldersidcontactsid-patch
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
      - Contact
  /users/{id | userPrincipalName}/contactFolders/{id}/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontactsid-patch
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
      - Contact
  /me/contactFolder/{id}/childFolders/{id}/.../contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: mecontactfolderidchildfoldersid---contactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: mecontactfolderidchildfoldersid---contactsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: mecontactfolderidchildfoldersid---contactsid-patch
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
      - Contact
  /users/{id | userPrincipalName}/contactFolders/{id}/childFolders/{id}/contacts/{id}:
    delete:
      summary: Delete Contact
      description: Delete contact Delete a contact.
      operationId: DeleteContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
    patch:
      summary: Update Contact
      description: Update contact Update the properties of a contact object.
      operationId: UpdateContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch
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
      - Contact
  /me/contactfolders/{Id}/contacts/{id}:
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: mecontactfoldersidcontactsid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
  /users/{id | userPrincipalName}/contactfolders/{id}/contacts/{id}:
    get:
      summary: Get Contact
      description: Get contact Retrieve the properties and relationships of a contact
        object.
      operationId: GetContact
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidcontactsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
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
      - Contact
  /me/contactFolders/{id}:
    delete:
      summary: Delete Contact Folder
      description: Delete contactFolder Delete contactFolder other than the default
        contactFolder.
      operationId: DeleteContactFolder
      x-api-path-slug: mecontactfoldersid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Folder
    get:
      summary: Get Contact Folder
      description: Get contactFolder Get a contact folder by using the contact folder
        ID.
      operationId: GetContactFolder
      x-api-path-slug: mecontactfoldersid-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Folder
  /users/{id | userPrincipalName}/contactFolders/{id}:
    delete:
      summary: Delete Contact Folder
      description: Delete contactFolder Delete contactFolder other than the default
        contactFolder.
      operationId: DeleteContactFolder
      x-api-path-slug: usersid--userprincipalnamecontactfoldersid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
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
      - Contact
      - Folder
    get:
      summary: Get Contact Folder
      description: Get contactFolder Get a contact folder by using the contact folder
        ID.
      operationId: GetContactFolder
      x-api-path-slug: usersid--userprincipalnamecontactfoldersid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
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
      - Contact
      - Folder
  /me/contactFolders/{id}/childFolders:
    post:
      summary: Create Contact Folder
      description: Create ContactFolder Create a new contactFolder as a child of a
        specified folder.
      operationId: CreateContactFolder
      x-api-path-slug: mecontactfoldersidchildfolders-post
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
      - Contact
      - Folder
  /users/{id | userPrincipalName}/contactFolders/{id}/childFolders:
    post:
      summary: Create Contact Folder
      description: Create ContactFolder Create a new contactFolder as a child of a
        specified folder.
      operationId: CreateContactFolder
      x-api-path-slug: usersid--userprincipalnamecontactfoldersidchildfolders-post
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
      - Contact
      - Folder
  /users/{id | userPrincipalName}/contactFolders:
    get:
      summary: List Contact Folders
      description: List contactFolders Get the contact folder collection in the default
        Contacts folder of the signed-in user.
      operationId: ListContactFolders
      x-api-path-slug: usersid--userprincipalnamecontactfolders-get
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
      - Contact
      - Folders
    post:
      summary: Create Contact Folder
      description: Create ContactFolder Create a new contactFolder under the user's
        default contacts folder.
      operationId: CreateContactFolder
      x-api-path-slug: usersid--userprincipalnamecontactfolders-post
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
      - Contact
      - Folder
  /me/contactFolders/{contactFolderId}/contacts:
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: mecontactfolderscontactfolderidcontacts-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: contactFolderId
        type: string
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Contact
  /users/{id | userPrincipalName}/contactFolders/{contactFolderId}/contacts:
    post:
      summary: Create Contact
      description: Create Contact Add a contact to the root Contacts folder or to
        the contacts endpoint of another contact folder.
      operationId: CreateContact
      x-api-path-slug: usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: path
        name: contactFolderId
        type: string
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