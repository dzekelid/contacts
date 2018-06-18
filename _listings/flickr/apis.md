---
name: Flickr
x-slug: flickr
description: Flickr (pronounced flicker) is an image hosting and video hosting website,
  and web services suite that was created by Ludicorp in 2004 and acquired by Yahoo
  in 2005. In addition to being a popular website for users to share and embed personal
  photographs, and effectively an online community, the service is widely used by
  photo researchers and by bloggers to host images that they embed in blogs and social
  media.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Contacts
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/apis.md
specificationVersion: "0.14"
apis:
- name: Flickr Contacts Get List
  x-api-slug: flickr
  description: Get a list of contacts for the calling user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.contacts.getList
  tags: Contacts,GetList
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-contacts-getlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-contacts-getlist-get-openapi.md
- name: Flickr Contacts Get List Recently Uploaded
  x-api-slug: flickr
  description: Return a list of contacts for a user who have recently uploaded photos
    along with the total count of photos uploaded. This method is still considered
    experimental. We don't plan for it to change or to go away but so long as this
    notice is present you should write your code accordingly.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.contacts.getListRecentlyUploaded
  tags: Contacts,GetListRecentlyUploaded
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-contacts-getlistrecentlyuploaded-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-contacts-getlistrecentlyuploaded-get-openapi.md
- name: Flickr Contacts Get Public List
  x-api-slug: flickr
  description: Get the contact list for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.contacts.getPublicList
  tags: Contacts,GetPublicList
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-contacts-getpubliclist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-contacts-getpubliclist-get-openapi.md
- name: Flickr Photos Get Contacts Photos
  x-api-slug: flickr
  description: Fetch a list of recent photos from the calling users' contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.getContactsPhotos
  tags: Photos,GetContactsPhotos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-photos-getcontactsphotos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-photos-getcontactsphotos-get-openapi.md
- name: Flickr Photos Get Contacts Public Photos
  x-api-slug: flickr
  description: Fetch a list of recent public photos from a users' contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.getContactsPublicPhotos
  tags: Photos,GetContactsPublicPhotos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-photos-getcontactspublicphotos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-photos-getcontactspublicphotos-get-openapi.md
- name: Flickr Photos Comments Get Recent For Contacts
  x-api-slug: flickr
  description: Return the list of photos belonging to your contacts that have been
    commented on recently.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.comments.getRecentForContacts
  tags: Photos,Comments,GetRecentForContacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-photos-comments-getrecentforcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-photos-comments-getrecentforcontacts-get-openapi.md
- name: Flickr Places Places For Contacts
  x-api-slug: flickr
  description: Return a list of the top 100 unique places clustered by a given placetype
    for a user's contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.places.placesForContacts
  tags: Places,PlacesForContacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-places-placesforcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/restmethodflickr-places-placesforcontacts-get-openapi.md
- name: Flickr
  x-api-slug: flickr
  description: The Flickr API consists of a set of callable methods, and some API
    endpoints.  To perform an action using the Flickr API, you need to select a calling
    convention, send a request to its endpoint specifying a method and some arguments,
    and will receive a formatted response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/contacts/master/_listings/flickr/openapi.md
x-common:
- type: x-authentication
  url: https://www.flickr.com/services/api/auth.oauth.html
- type: x-base
  url: https://api.flickr.com/services/
- type: x-developer
  url: https://www.flickr.com/services/api/
- type: x-getting-started
  url: https://www.flickr.com/services/developer/
- type: x-privacy
  url: https://info.yahoo.com/privacy/us/yahoo/flickr/details.html
- type: x-support
  url: https://help.yahoo.com/kb/flickr-for-desktop
- type: x-terms-of-service
  url: https://www.flickr.com/services/api/tos/
- type: x-twitter
  url: https://twitter.com/flickr
- type: x-website
  url: http://www.flickr.com/
- type: x-website
  url: http://flickr.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---