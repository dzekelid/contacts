---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Search contacts based on the phone number provided
  version: 1.0.0
  description: Search contacts based on the phone number provided.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/people/searchcontacts:
    post:
      summary: Search contacts based on the phone number provided
      description: Search contacts based on the phone number provided.
      operationId: People_SearchContactsBysearchCommandDataContract
      x-api-path-slug: apipeoplesearchcontacts-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: searchCommandDataContract
        description: Search data contract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Search
      - Contacts
      - Based
      - "On"
      - Phone
      - Number
      - Provided
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