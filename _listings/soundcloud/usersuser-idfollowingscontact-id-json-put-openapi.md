---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 0
info:
  title: Sound Cloud Put Users Followings Contact
  description: Adds the user with the id contact_id to the givens user's list of contacts.
  version: 1.0.0
host: api.soundcloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/followings/{contact_id}.json:
    get:
      summary: Get Users Followings Contact
      description: Checks if the user with the id contact_id is in the givens user's
        list of contacts.
      operationId: getUsersUserFollowingsContact.json
      x-api-path-slug: usersuser-idfollowingscontact-id-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followings
      - Contact
    put:
      summary: Put Users Followings Contact
      description: Adds the user with the id contact_id to the givens user's list
        of contacts.
      operationId: putUsersUserFollowingsContact.json
      x-api-path-slug: usersuser-idfollowingscontact-id-json-put
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followings
      - Contact
    delete:
      summary: Delete Users Followings Contact
      description: Removes the user with the id contact_id from the givens user's
        list of contacts.
      operationId: deleteUsersUserFollowingsContact.json
      x-api-path-slug: usersuser-idfollowingscontact-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followings
      - Contact
  /users/{user_id}/followers/{contact_id}.json:
    get:
      summary: Get Users Followers Contact
      description: Checks if the user with contact_id is a follower of the given user.
      operationId: getUsersUserFollowersContact.json
      x-api-path-slug: usersuser-idfollowerscontact-id-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followers
      - Contact
  /me/followings/{contact_id}.json:
    get:
      summary: Get Me Followings Contact
      description: Checks if the user with the id contact_id is in the logged-in user's
        list of contacts.
      operationId: getMeFollowingsContact.json
      x-api-path-slug: mefollowingscontact-id-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
    put:
      summary: Put Me Followings Contact
      description: Adds the user with the id contact_id to the logged-in user's list
        of contacts.
      operationId: putMeFollowingsContact.json
      x-api-path-slug: mefollowingscontact-id-json-put
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
    delete:
      summary: Delete Me Followings Contact
      description: Deletes the user with the id contact_id from the logged-in user's
        list of contacts.
      operationId: deleteMeFollowingsContact.json
      x-api-path-slug: mefollowingscontact-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
  /me/followers/{contact_id}.json:
    get:
      summary: Get Me Followers Contact
      description: Checks if the user with the id contact_id is a follower of the
        logged-in user
      operationId: getMeFollowersContact.json
      x-api-path-slug: mefollowerscontact-id-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followers
      - Contact
  /users/{user_id}/followings/{contact_id}.{format}:
    get:
      summary: Get Users Followings Contact . Format
      description: Checks if the user with the id contact_id is in the givens user's
        list of contacts.
      operationId: getUsersUserFollowingsContact.Format
      x-api-path-slug: usersuser-idfollowingscontact-id-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      - in: path
        name: user_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followings
      - Contact
      - ""
      - ""
      - Format
    put:
      summary: Put Users Followings Contact . Format
      description: Adds the user with the id contact_id to the givens user's list
        of contacts.
      operationId: putUsersUserFollowingsContact.Format
      x-api-path-slug: usersuser-idfollowingscontact-id-format-put
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      - in: path
        name: user_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followings
      - Contact
      - ""
      - ""
      - Format
    delete:
      summary: Delete Users Followings Contact . Format
      description: Removes the user with the id contact_id from the givens user's
        list of contacts.
      operationId: deleteUsersUserFollowingsContact.Format
      x-api-path-slug: usersuser-idfollowingscontact-id-format-delete
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      - in: path
        name: user_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followings
      - Contact
      - ""
      - ""
      - Format
  /users/{user_id}/followers/{contact_id}.{format}:
    get:
      summary: Get Users Followers Contact . Format
      description: Checks if the user with contact_id is a follower of the given user.
      operationId: getUsersUserFollowersContact.Format
      x-api-path-slug: usersuser-idfollowerscontact-id-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      - in: path
        name: user_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followers
      - Contact
      - ""
      - ""
      - Format
  /me/followings/{contact_id}.{format}:
    get:
      summary: Get Me Followings Contact . Format
      description: Checks if the user with the id contact_id is in the logged-in user's
        list of contacts.
      operationId: getMeFollowingsContact.Format
      x-api-path-slug: mefollowingscontact-id-format-get
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
      - ""
      - ""
      - Format
    put:
      summary: Put Me Followings Contact . Format
      description: Adds the user with the id contact_id to the logged-in user's list
        of contacts.
      operationId: putMeFollowingsContact.Format
      x-api-path-slug: mefollowingscontact-id-format-put
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
      - ""
      - ""
      - Format
    delete:
      summary: Delete Me Followings Contact . Format
      description: Deletes the user with the id contact_id from the logged-in user's
        list of contacts.
      operationId: deleteMeFollowingsContact.Format
      x-api-path-slug: mefollowingscontact-id-format-delete
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
      - ""
      - ""
      - Format
  /me/followers/{contact_id}.{format}:
    get:
      summary: Get Me Followers Contact . Format
      description: Checks if the user with the id contact_id is a follower of the
        logged-in user
      operationId: getMeFollowersContact.Format
      x-api-path-slug: mefollowerscontact-id-format-get
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followers
      - Contact
      - ""
      - ""
      - Format
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