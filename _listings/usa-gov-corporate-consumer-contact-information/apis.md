---
name: USA.Gov Corporate Consumer Contact Information
x-slug: usa-gov-corporate-consumer-contact-information
description: We make the Corporate Consumer Contact listing found in the Consumer
  Action Handbook (PDF) available via a REST API. The API programmatically returns
  all of the information contained in the directory, or you can query the API to return
  just a subset of the available information.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Contacts
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/usa-gov-corporate-consumer-contact-information/apis.md
specificationVersion: "0.14"
apis:
- name: USA.Gov Corporate Consumer Contact API Get Contacts
  x-api-slug: usa-gov-corporate-consumer-contact-api
  description: Contacts is a general purpose call that, by default, will return all
    of the corporate directory records. However, you can pass parameters into the
    contacts call that allow you to filter the records returned by the API in powerful
    ways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://github.com/usagov/Corporate-Consumer-Contact-API-Documentation
  baseURL: https://www.usa.gov/api/USAGovAPI///contacts.{format}/contacts
  tags: Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/usa-gov-corporate-consumer-contact-information/contacts-formatcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/usa-gov-corporate-consumer-contact-information/contacts-formatcontacts-get-openapi.md
- name: USA.Gov Corporate Consumer Contact API Get Contact
  x-api-slug: usa-gov-corporate-consumer-contact-api
  description: The Contact call will let you access an individual corporation's information
    by including its unique identifier in the call.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://github.com/usagov/Corporate-Consumer-Contact-API-Documentation
  baseURL: https://www.usa.gov/api/USAGovAPI///contacts.{format}/contacts/{id}
  tags: Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/usa-gov-corporate-consumer-contact-information/contacts-formatcontactsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/usa-gov-corporate-consumer-contact-information/contacts-formatcontactsid-get-openapi.md
- name: USA.Gov Corporate Consumer Contact API
  x-api-slug: usa-gov-corporate-consumer-contact-api
  description: We make the Corporate Consumer Contact listing found in theConsumer
    Action Handbook (PDF)available via a REST API. The API programmatically returns
    all of the information contained in the directory, or you can query the API to
    return just a subset of the available information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/usa-gov-logo.png
  humanURL: https://github.com/usagov/Corporate-Consumer-Contact-API-Documentation
  baseURL: https://www.usa.gov/api/USAGovAPI/
  tags: Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/usa-gov-corporate-consumer-contact-information/openapi.md
x-common:
- type: x-terms-of-service
  url: https://www.usa.gov/developer-terms-of-service
- type: x-website
  url: https://github.com/usagov/Corporate-Consumer-Contact-API-Documentation
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---