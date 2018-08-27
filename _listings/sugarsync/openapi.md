swagger: "2.0"
x-collection-name: SugarSync
x-complete: 1
info:
  title: SugarSync  API
  description: the-sugarsync-service-presents-a-set-of-resources-that-your-application-can-access-through-the-platform-api--
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