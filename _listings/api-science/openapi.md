swagger: "2.0"
x-collection-name: API Science
x-complete: 1
info:
  title: API Science
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contacts.json:
    get:
      summary: Get All Contacts
      description: Get All Contacts
      operationId: getAllContacts
      x-api-path-slug: contacts-json-get
      responses:
        200:
          description: OK
      tags:
      - Contacts
    post:
      summary: Create a Contact
      description: Create a Contact
      operationId: createContact
      x-api-path-slug: contacts-json-post
      parameters:
      - in: formData
        name: label
        description: User-defined label for this contact
      - in: formData
        name: type
        description: 'Type of contact, options are: email, url, pagerduty'
      - in: formData
        name: value
        description: 'Contents of value vary based on the type of contact being created:
          an email address, a URL or your PagerDuty API key'
      responses:
        200:
          description: OK
      tags:
      - Contacts
  /contacts/{id}.json:
    delete:
      summary: Delete a Contact
      description: Delete a Contact
      operationId: deleteContact
      x-api-path-slug: contactsid-json-delete
      parameters:
      - in: path
        name: id
        description: The id for the contact
      responses:
        200:
          description: OK
      tags:
      - Contacts
    get:
      summary: Get a Specific Contact
      description: Get a Specific Contact
      operationId: getContact
      x-api-path-slug: contactsid-json-get
      parameters:
      - in: path
        name: id
        description: The ID of the contact to retrieve
      responses:
        200:
          description: OK
      tags:
      - Contacts
    patch:
      summary: Update a Contact
      description: Update a Contact
      operationId: updateContact
      x-api-path-slug: contactsid-json-patch
      parameters:
      - in: path
        name: id
        description: ID for the contact
      - in: formData
        name: label
        description: User-defined label for this contact
      - in: formData
        name: type
        description: 'Type of contact, options are: email, url, pagerduty'
      - in: query
        name: value
        description: 'Contents of value vary based on the type of contact being created:
          an email address, a URL or your PagerDuty API key'
      responses:
        200:
          description: OK
      tags:
      - Contacts
  ? |2-

        /api/{version}/contacts
  : ? |2-

          get
    : summary: Get Contacts List
      description: Returns a list of all contacts.
      operationId: get-contacts-list
      x-api-path-slug: apiversioncontacts-get
      parameters:
      - in: query
        name: limit
        description: Limits the number of returned contacts to the specified quantity
        type: <td>integer</td>
      - in: query
        name: offset
        description: Offset for listing
        type: <td>integer</td>
      responses:
        200:
          description: OK
      tags:
      - Contacts