---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/directorySiteContacts:
    get:
      summary: Get Directory Site Contacts
      description: Retrieves a list of directory site contacts, possibly filtered.
        This method supports paging.
      operationId: dfareporting.directorySiteContacts.list
      x-api-path-slug: userprofilesprofileiddirectorysitecontacts-get
      parameters:
      - in: query
        name: directorySiteIds
        description: Select only directory site contacts with these directory site
          IDs
      - in: query
        name: ids
        description: Select only directory site contacts with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name, ID or email
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Contact
  /userprofiles/{profileId}/directorySiteContacts/{id}:
    get:
      summary: Get Directory Site Contact
      description: Gets one directory site contact by ID.
      operationId: dfareporting.directorySiteContacts.get
      x-api-path-slug: userprofilesprofileiddirectorysitecontactsid-get
      parameters:
      - in: path
        name: id
        description: Directory site contact ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Contact
---