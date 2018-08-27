---
swagger: "2.0"
x-collection-name: SugarSync
x-complete: 0
info:
  title: Sugar Sync  API Retrieving Contact Information
  description: A contact represents another SugarSync user who has shared a folder
    or folders with this user.n          To retrieve information about a contact,
    an application submits an HTTP GET request to then          contact resource.
  version: "1"
host: api.sugarsync.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contact/:
    get:
      summary: Retrieving Contact Information
      description: A contact represents another SugarSync user who has shared a folder
        or folders with this user.n          To retrieve information about a contact,
        an application submits an HTTP GET request to then          contact resource.
      operationId: retrieving-contact-information
      x-api-path-slug: contact-get
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