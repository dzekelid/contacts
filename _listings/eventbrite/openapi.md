---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 1
info:
  title: Eventbrite
  description: create-manage--promote-events--add-eventmanagement-features-to-your-site--show-the-world-what-exciting-things-are-happening-around-them-
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
    post:
      summary: Post Users Contact Lists Contact List Contacts
      description: 'Adds a new contact to the contact list. Returns {&quot;created&quot;:
        true}.'
      operationId: postUsersContactListsContactListContacts
      x-api-path-slug: usersidcontact-listscontact-list-idcontacts-post
      parameters:
      - in: query
        name: contact.email
        description: Contact&#8217;s email address
        type: query
      - in: query
        name: contact.first_name
        description: Contact&#8217;s first name (or full name)
        type: query
      - in: query
        name: contact.last_name
        description: Contact&#8217;s last name
        type: query
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
    delete:
      summary: Delete Users Contact Lists Contact List Contacts
      description: |-
        Deletes the specified contact from the contact list.
        Returns {&quot;deleted&quot;: true}.
      operationId: deleteUsersContactListsContactListContacts
      x-api-path-slug: usersidcontact-listscontact-list-idcontacts-delete
      parameters:
      - in: query
        name: email
        description: Email address to remove
        type: query
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
---