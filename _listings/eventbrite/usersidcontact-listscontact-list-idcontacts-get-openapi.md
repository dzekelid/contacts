---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get Users Contact Lists Contact List Contacts
  description: |-
    Returns the contacts on the contact list
    as contacts.
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id}/contact_lists/:contact_list_id/contacts/:
    get:
      summary: Get Users Contact Lists Contact List Contacts
      description: |-
        Returns the contacts on the contact list
        as contacts.
      operationId: getUsersContactListsContactListContacts
      x-api-path-slug: usersidcontact-listscontact-list-idcontacts-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Contact
      - Lists
      - :contact
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