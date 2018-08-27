---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Contacts
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API - List Contacts
  x-api-slug: mecontacts-get
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontacts-get-openapi.md
- name: Microsoft Graph API - List Contacts
  x-api-slug: usersid--userprincipalnamecontacts-get
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-get-openapi.md
- name: Microsoft Graph API - List Contacts
  x-api-slug: mecontactfoldersidcontacts-get
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontacts-get-openapi.md
- name: Microsoft Graph API - List Contacts
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontacts-get
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user (.../me/contacts), or from the specified contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-get-openapi.md
- name: Microsoft Graph API - List Contacts
  x-api-slug: mecontactfolderidchildfoldersid---contacts-get
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contacts-get-openapi.md
- name: Microsoft Graph API - List Contacts
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontacts-get
  description: List contacts Get a contact collection from the default Contacts folder
    of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontacts-get-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: mecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: mecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: mecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontactfoldersidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-post-openapi.md
- name: Microsoft Graph API - List Contact Folders
  x-api-slug: usersid--userprincipalnamecontactfolders-get
  description: List contactFolders Get the contact folder collection in the default
    Contacts folder of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-get-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfolders-post
  description: Create ContactFolder Create a new contactFolder under the user's default
    contacts folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontactfolderscontactfolderidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderscontactfolderidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderscontactfolderidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: mecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: mecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: mecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontactfoldersidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-post-openapi.md
- name: Microsoft Graph API - List Contact Folders
  x-api-slug: usersid--userprincipalnamecontactfolders-get
  description: List contactFolders Get the contact folder collection in the default
    Contacts folder of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-get-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfolders-post
  description: Create ContactFolder Create a new contactFolder under the user's default
    contacts folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontactfolderscontactfolderidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderscontactfolderidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderscontactfolderidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolderscontactfolderidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontactfolderscontactfolderidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderscontactfolderidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderscontactfolderidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfolders-post
  description: Create ContactFolder Create a new contactFolder under the user's default
    contacts folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-post-openapi.md
- name: Microsoft Graph API - List Contact Folders
  x-api-slug: usersid--userprincipalnamecontactfolders-get
  description: List contactFolders Get the contact folder collection in the default
    Contacts folder of the signed-in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfolders-get-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontactfoldersidcontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: usersid--userprincipalnamecontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact
  x-api-slug: mecontacts-post
  description: Create Contact Add a contact to the root Contacts folder or to the
    contacts endpoint of another contact folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontacts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontacts-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Create Contact Folder
  x-api-slug: mecontactfoldersidchildfolders-post
  description: Create ContactFolder Create a new contactFolder as a child of a specified
    folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidchildfolders-post-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Get Contact Folder
  x-api-slug: mecontactfoldersid-get
  description: Get contactFolder Get a contact folder by using the contact folder
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-get-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: usersid--userprincipalnamecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact Folder
  x-api-slug: mecontactfoldersid-delete
  description: Delete contactFolder Delete contactFolder other than the default contactFolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersid-delete-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactfoldersidcontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: usersid--userprincipalnamecontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-patch-openapi.md
- name: Microsoft Graph API - Update Contact
  x-api-slug: mecontactsid-patch
  description: Update contact Update the properties of a contact object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-patch-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactfoldersidcontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: usersid--userprincipalnamecontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-get-openapi.md
- name: Microsoft Graph API - Get Contact
  x-api-slug: mecontactsid-get
  description: Get contact Retrieve the properties and relationships of a contact
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-get-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidchildfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactfolderidchildfoldersid---contactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfolderidchildfoldersid---contactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactfoldersidcontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactfoldersidcontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: usersid--userprincipalnamecontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/usersid--userprincipalnamecontactsid-delete-openapi.md
- name: Microsoft Graph API - Delete Contact
  x-api-slug: mecontactsid-delete
  description: Delete contact Delete a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/microsoft-graph/mecontactsid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://messente.api.gallery.streamdata.io
- type: x-api-stack
  url: http://microsoft.graph.stack.network
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---