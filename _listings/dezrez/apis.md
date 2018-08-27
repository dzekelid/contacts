---
name: Dezrez
x-slug: dezrez
description: Cloud based estate agent software , sales & letting agent software, estate
  agent website design and property management software - Dezrez  Services
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
x-kinRank: "7"
x-alexaRank: "385559"
tags: Contacts
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apis.md
specificationVersion: "0.14"
apis:
- name: Dezrez.Rezi.Client.Api - Search contacts based on the phone number provided
  x-api-slug: apipeoplesearchcontacts-post
  description: Search contacts based on the phone number provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeoplesearchcontacts-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to the given auction Role or edit
    an existing contact
  x-api-slug: apiauctionsavecontact-post
  description: Add a new contact to the given auction role or edit an existing contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiauctionsavecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove an existing auction contact from the auction
    role
  x-api-slug: apiauctionremovecontact-post
  description: Remove an existing auction contact from the auction role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiauctionremovecontact-post-openapi.md
- name: "Dezrez.Rezi.Client.Api - Generates a bulk communication pack out to multiple
    vendors of properties.\r\nThis will ignore the target type set, as the document
    could only ever find the vendor as the contact item, so it always defaults\r\nto
    a target type of vendor/owner"
  x-api-slug: apidocumentgenerationbulkpropertyownercommunication-post
  description: "Generates a bulk communication pack out to multiple vendors of properties.\r\nthis
    will ignore the target type set, as the document could only ever find the vendor
    as the contact item, so it always defaults\r\nto a target type of vendor/owner."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apidocumentgenerationbulkpropertyownercommunication-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact with a person
  x-api-slug: apieventrecordenquiry-post
  description: Records an event on the role representing a neg being in contact with
    a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordenquiry-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Delete a contact from a group
  x-api-slug: apigroupiddeletegroupmember-delete
  description: Delete a contact from a group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigroupiddeletegroupmember-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to an existing group
  x-api-slug: apigroupidaddgroupmember-put
  description: Add a new contact to an existing group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigroupidaddgroupmember-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the group representing a neg
    being in contact
  x-api-slug: apigrouprecordcontact-post
  description: Records an event on the group representing a neg being in contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigrouprecordcontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Check for Matching groups for the given leads based
    on contact item values i.e. Emails and Phones.
  x-api-slug: apiinboundleadcheckformatchinggroups-get
  description: Check for matching groups for the given leads based on contact item
    values i.e. emails and phones..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiinboundleadcheckformatchinggroups-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Get All contact items for a person, but obscure the
    details
  x-api-slug: apipeopleunsubscribeid-get
  description: Get all contact items for a person, but obscure the details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleunsubscribeid-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Unsubscribe/Subscribe All contact items for a person
  x-api-slug: apipeopleunsubscribeid-post
  description: Unsubscribe/subscribe all contact items for a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleunsubscribeid-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to the given progression Role or
    edit an existing contact
  x-api-slug: apiprogressionsavecontact-post
  description: Add a new contact to the given progression role or edit an existing
    contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressionsavecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove an existing progression contact from the progression
    role
  x-api-slug: apiprogressionremovecontact-post
  description: Remove an existing progression contact from the progression role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressionremovecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact for a property they own
  x-api-slug: apieventrecordpropertyownercontact-post
  description: Records an event on the role representing a neg being in contact for
    a property they own.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordpropertyownercontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact for an owner
  x-api-slug: apieventrecordownercontact-post
  description: Records an event on the role representing a neg being in contact for
    an owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordownercontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a ContactItem to a Person
  x-api-slug: apipeopleidaddcontactitem-post
  description: Add a contactitem to a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleidaddcontactitem-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove a ContactItem from a Person
  x-api-slug: apipeopleidremovecontactitemcontactitemid-put
  description: Remove a contactitem from a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleidremovecontactitemcontactitemid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Get all progression contacts for the given progression
    role
  x-api-slug: apiprogressiongetallcontacts-get
  description: Get all progression contacts for the given progression role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressiongetallcontacts-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to the given auction Role or edit
    an existing contact
  x-api-slug: apiauctionsavecontact-post
  description: Add a new contact to the given auction role or edit an existing contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiauctionsavecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove an existing auction contact from the auction
    role
  x-api-slug: apiauctionremovecontact-post
  description: Remove an existing auction contact from the auction role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiauctionremovecontact-post-openapi.md
- name: "Dezrez.Rezi.Client.Api - Generates a bulk communication pack out to multiple
    vendors of properties.\r\nThis will ignore the target type set, as the document
    could only ever find the vendor as the contact item, so it always defaults\r\nto
    a target type of vendor/owner"
  x-api-slug: apidocumentgenerationbulkpropertyownercommunication-post
  description: "Generates a bulk communication pack out to multiple vendors of properties.\r\nthis
    will ignore the target type set, as the document could only ever find the vendor
    as the contact item, so it always defaults\r\nto a target type of vendor/owner."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apidocumentgenerationbulkpropertyownercommunication-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact with a person
  x-api-slug: apieventrecordenquiry-post
  description: Records an event on the role representing a neg being in contact with
    a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordenquiry-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Delete a contact from a group
  x-api-slug: apigroupiddeletegroupmember-delete
  description: Delete a contact from a group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigroupiddeletegroupmember-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to an existing group
  x-api-slug: apigroupidaddgroupmember-put
  description: Add a new contact to an existing group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigroupidaddgroupmember-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the group representing a neg
    being in contact
  x-api-slug: apigrouprecordcontact-post
  description: Records an event on the group representing a neg being in contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigrouprecordcontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Check for Matching groups for the given leads based
    on contact item values i.e. Emails and Phones.
  x-api-slug: apiinboundleadcheckformatchinggroups-get
  description: Check for matching groups for the given leads based on contact item
    values i.e. emails and phones..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiinboundleadcheckformatchinggroups-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Get All contact items for a person, but obscure the
    details
  x-api-slug: apipeopleunsubscribeid-get
  description: Get all contact items for a person, but obscure the details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleunsubscribeid-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Unsubscribe/Subscribe All contact items for a person
  x-api-slug: apipeopleunsubscribeid-post
  description: Unsubscribe/subscribe all contact items for a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleunsubscribeid-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to the given progression Role or
    edit an existing contact
  x-api-slug: apiprogressionsavecontact-post
  description: Add a new contact to the given progression role or edit an existing
    contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressionsavecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove an existing progression contact from the progression
    role
  x-api-slug: apiprogressionremovecontact-post
  description: Remove an existing progression contact from the progression role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressionremovecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a ContactItem to a Person
  x-api-slug: apipeopleidaddcontactitem-post
  description: Add a contactitem to a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleidaddcontactitem-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove a ContactItem from a Person
  x-api-slug: apipeopleidremovecontactitemcontactitemid-put
  description: Remove a contactitem from a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleidremovecontactitemcontactitemid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact for a property they own
  x-api-slug: apieventrecordpropertyownercontact-post
  description: Records an event on the role representing a neg being in contact for
    a property they own.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordpropertyownercontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact for an owner
  x-api-slug: apieventrecordownercontact-post
  description: Records an event on the role representing a neg being in contact for
    an owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordownercontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a ContactItem to a Person
  x-api-slug: apipeopleidaddcontactitem-post
  description: Add a contactitem to a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleidaddcontactitem-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove a ContactItem from a Person
  x-api-slug: apipeopleidremovecontactitemcontactitemid-put
  description: Remove a contactitem from a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleidremovecontactitemcontactitemid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Get all progression contacts for the given progression
    role
  x-api-slug: apiprogressiongetallcontacts-get
  description: Get all progression contacts for the given progression role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressiongetallcontacts-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove an existing progression contact from the progression
    role
  x-api-slug: apiprogressionremovecontact-post
  description: Remove an existing progression contact from the progression role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressionremovecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to the given progression Role or
    edit an existing contact
  x-api-slug: apiprogressionsavecontact-post
  description: Add a new contact to the given progression role or edit an existing
    contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressionsavecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Unsubscribe/Subscribe All contact items for a person
  x-api-slug: apipeopleunsubscribeid-post
  description: Unsubscribe/subscribe all contact items for a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleunsubscribeid-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Get All contact items for a person, but obscure the
    details
  x-api-slug: apipeopleunsubscribeid-get
  description: Get all contact items for a person, but obscure the details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleunsubscribeid-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Check for Matching groups for the given leads based
    on contact item values i.e. Emails and Phones.
  x-api-slug: apiinboundleadcheckformatchinggroups-get
  description: Check for matching groups for the given leads based on contact item
    values i.e. emails and phones..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiinboundleadcheckformatchinggroups-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the group representing a neg
    being in contact
  x-api-slug: apigrouprecordcontact-post
  description: Records an event on the group representing a neg being in contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigrouprecordcontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to an existing group
  x-api-slug: apigroupidaddgroupmember-put
  description: Add a new contact to an existing group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigroupidaddgroupmember-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Delete a contact from a group
  x-api-slug: apigroupiddeletegroupmember-delete
  description: Delete a contact from a group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apigroupiddeletegroupmember-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact with a person
  x-api-slug: apieventrecordenquiry-post
  description: Records an event on the role representing a neg being in contact with
    a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordenquiry-post-openapi.md
- name: "Dezrez.Rezi.Client.Api - Generates a bulk communication pack out to multiple
    vendors of properties.\r\nThis will ignore the target type set, as the document
    could only ever find the vendor as the contact item, so it always defaults\r\nto
    a target type of vendor/owner"
  x-api-slug: apidocumentgenerationbulkpropertyownercommunication-post
  description: "Generates a bulk communication pack out to multiple vendors of properties.\r\nthis
    will ignore the target type set, as the document could only ever find the vendor
    as the contact item, so it always defaults\r\nto a target type of vendor/owner."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apidocumentgenerationbulkpropertyownercommunication-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove an existing auction contact from the auction
    role
  x-api-slug: apiauctionremovecontact-post
  description: Remove an existing auction contact from the auction role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiauctionremovecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a new contact to the given auction Role or edit
    an existing contact
  x-api-slug: apiauctionsavecontact-post
  description: Add a new contact to the given auction role or edit an existing contact.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiauctionsavecontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact for a property they own
  x-api-slug: apieventrecordpropertyownercontact-post
  description: Records an event on the role representing a neg being in contact for
    a property they own.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordpropertyownercontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Records an event on the role representing a neg being
    in contact for an owner
  x-api-slug: apieventrecordownercontact-post
  description: Records an event on the role representing a neg being in contact for
    an owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apieventrecordownercontact-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Remove a ContactItem from a Person
  x-api-slug: apipeopleidremovecontactitemcontactitemid-put
  description: Remove a contactitem from a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleidremovecontactitemcontactitemid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Add a ContactItem to a Person
  x-api-slug: apipeopleidaddcontactitem-post
  description: Add a contactitem to a person.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apipeopleidaddcontactitem-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Get all progression contacts for the given progression
    role
  x-api-slug: apiprogressiongetallcontacts-get
  description: Get all progression contacts for the given progression role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/dezrez/apiprogressiongetallcontacts-get-openapi.md
x-common:
- type: x-github
  url: https://github.com/dezrez
- type: x-openapi
  url: https://api.dezrez.com:443/swagger/docs/v1
- type: x-api-gallery
  url: http://datumbox.api.gallery.streamdata.io
- type: x-api-stack
  url: http://dezrez.stack.network
- type: x-documentation
  url: https://api.dezrez.com/swagger/ui/index#!/AccountingExport
- type: x-support
  url: https://www.dezrez.com/uk/estate-agency-software-support
- type: x-twitter
  url: https://twitter.com/dezrezsoftware
- type: x-website
  url: https://www.dezrez.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---