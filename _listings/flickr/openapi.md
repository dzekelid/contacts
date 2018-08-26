---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.contacts.getList:
    get:
      summary: Contacts Get List
      description: Get a list of contacts for the calling user.
      operationId: getRestMethodFlickr.contacts.getlist
      x-api-path-slug: restmethodflickr-contacts-getlist-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: filter
        description: An optional filter of the results
      - in: query
        name: format
        description: Response format
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of photos to return per page
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - GetList
  /rest/?method=flickr.contacts.getListRecentlyUploaded:
    get:
      summary: Contacts Get List Recently Uploaded
      description: Return a list of contacts for a user who have recently uploaded
        photos along with the total count of photos uploaded. This method is still
        considered experimental. We don't plan for it to change or to go away but
        so long as this notice is present you should write your code accordingly.
      operationId: getRestMethodFlickr.contacts.getlistrecentlyuploaded
      x-api-path-slug: restmethodflickr-contacts-getlistrecentlyuploaded-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: date_lastupload
        description: Limits the resultset to contacts that have uploaded photos since
          this date
      - in: query
        name: filter
        description: Limit the result set to all contacts or only those who are friends
          or family
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - GetListRecentlyUploaded
  /rest/?method=flickr.contacts.getPublicList:
    get:
      summary: Contacts Get Public List
      description: Get the contact list for a user.
      operationId: getRestMethodFlickr.contacts.getpubliclist
      x-api-path-slug: restmethodflickr-contacts-getpubliclist-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of photos to return per page
      - in: query
        name: user_id
        description: The NSID of the user to fetch the contact list for
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - GetPublicList
---