---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Deletes an account contact relation. The ID of the account
    contact relation must be specified.
  description: Deletes an account contact relation. the id of the account contact
    relation must be specified..
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/contacts:
    get:
      summary: List contacts
      description: List contacts.
      operationId: getRestAccountsContacts
      x-api-path-slug: restaccountscontacts-get
      parameters:
      - in: query
        name: billingAddressId
        description: Filter that restricts the search result to contacts with a billing
          address with the id provided
      - in: query
        name: contactAddress
        description: Filter that restricts the search result to contacts with a specific
          address
      - in: query
        name: contactEmail
        description: Filter that restricts the search result to contacts resembling
          to the given email address
      - in: query
        name: contactId
        description: Filter that restricts the search result to a specific contact
      - in: query
        name: countryId
        description: Filter that restricts the search result to contacts with a specific
          country
      - in: query
        name: createdAtAfter
        description: Filter that restricts the search result to contacts that were
          created after a specific date
      - in: query
        name: createdAtBefore
        description: Filter that restricts the search result to contacts that were
          created before a specific date
      - in: query
        name: deliveryAddressId
        description: Filter that restricts the search result to contacts with a delivery
          address with the id provided
      - in: query
        name: email
        description: Filter that restricts the search result to contacts with a specific
          email address
      - in: query
        name: externalId
        description: Filter that restricts the search result to contacts with a specific
          externalId
      - in: query
        name: fullText
        description: Filter for a fulltext search
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: name
        description: Filter that restricts the search result to contacts with a specific
          name
      - in: query
        name: newsletterAllowance
        description: Filter that restricts the search result to contacts who registered
          for the newsletter
      - in: query
        name: newsletterAllowanceAfter
        description: Filter that restricts the search result to contacts who registered
          for the newsletter after a specific date
      - in: query
        name: newsletterAllowanceBefore
        description: Filter that restricts the search result to contacts who registered
          for the newsletter before a specific date
      - in: query
        name: number
        description: Filter that restricts the search result to contacts with a specific
          number
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: plentyId
        description: Filter that restricts the search result to contacts with a specific
          plentyId
      - in: query
        name: postalCode
        description: Filter that restricts the search result to contacts with a specific
          postal code
      - in: query
        name: privatePhone
        description: Filter that restricts the search result to contacts with a private
          phone number
      - in: query
        name: referrerId
        description: Filter that restricts the search result to contacts with a specific
          referrer
      - in: query
        name: town
        description: Filter that restricts the search result to contacts with a specific
          town
      - in: query
        name: typeId
        description: Filter that restricts the search result to contacts with a specific
          contact type
      - in: query
        name: updatedAtAfter
        description: Filter that restricts the search result to contacts that were
          updated after a specific date
      - in: query
        name: updatedAtBefore
        description: Filter that restricts the search result to contacts that were
          updated before a specific date
      - in: query
        name: userId
        description: Filter that restricts the search result to contacts with a specific
          user
      - in: query
        name: with
        description: Includes the specified contact information in the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
    post:
      summary: Create a contact
      description: Create a contact.
      operationId: postRestAccountsContacts
      x-api-path-slug: restaccountscontacts-post
      parameters:
      - in: body
        name: /rest/accounts/contacts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
  /rest/accounts/contacts/{contactId}/addresses/{addressTypeId?}:
    get:
      summary: List addresses that are linked with contacts
      description: Lists addresses of the contact. The ID of the contact must be specified.
      operationId: getRestAccountsContactsContactAddressesAddresstype
      x-api-path-slug: restaccountscontactscontactidaddressesaddresstypeid-get
      parameters:
      - in: path
        name: addressTypeId?
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - List
      - Addresses
      - That
      - Are
      - Linked
      - Contacts
  /rest/accounts/{accountId}/contacts:
    get:
      summary: List contacts
      description: Lists contacts of the account. The ID of the account must be specified.
      operationId: getRestAccountsAccountContacts
      x-api-path-slug: restaccountsaccountidcontacts-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
  /rest/accounts/addresses/contact_relations:
    get:
      summary: List address contact relations
      description: List address contact relations.
      operationId: getRestAccountsAddressesContactRelations
      x-api-path-slug: restaccountsaddressescontact-relations-get
      parameters:
      - in: query
        name: addressId
        description: Filter that restricts the search result to addresses with a specific
          ID
      - in: query
        name: contactId
        description: Filter that restricts the search result to contacts with a specific
          ID
      - in: query
        name: id
        description: Filter that restricts the search result to address contact relations
          with a specific ID
      - in: query
        name: isPrimary
        description: Filter that restricts the search result depending on the flag
          used
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: typeId
        description: Filter that restricts the search result to address types with
          a specific ID
      - in: query
        name: with
        description: Includes the specified address contact relation information in
          the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Contact
      - Relations
    post:
      summary: Create address contact relations
      description: Create address contact relations.
      operationId: postRestAccountsAddressesContactRelations
      x-api-path-slug: restaccountsaddressescontact-relations-post
      parameters:
      - in: body
        name: /rest/accounts/addresses/contact_relations
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Address
      - Contact
      - Relations
    put:
      summary: Update address contact relations
      description: Update address contact relations.
      operationId: putRestAccountsAddressesContactRelations
      x-api-path-slug: restaccountsaddressescontact-relations-put
      parameters:
      - in: body
        name: /rest/accounts/addresses/contact_relations
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Address
      - Contact
      - Relations
  /rest/accounts/addresses/contact_relations/{addressContactRelationId}:
    delete:
      summary: Delete an address contact relation
      description: Deletes an address contact relation. The ID of the relation must
        be specified.
      operationId: deleteRestAccountsAddressesContactRelationsAddresscontactrelation
      x-api-path-slug: restaccountsaddressescontact-relationsaddresscontactrelationid-delete
      parameters:
      - in: path
        name: addressContactRelationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Contact
      - Relation
    get:
      summary: Get an address contact relation
      description: Gets an address contact relation. The ID of the address contact
        relation must be specified.
      operationId: getRestAccountsAddressesContactRelationsAddresscontactrelation
      x-api-path-slug: restaccountsaddressescontact-relationsaddresscontactrelationid-get
      parameters:
      - in: path
        name: addressContactRelationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Contact
      - Relation
  /rest/accounts/contact_relations/{accountContactRelationId}:
    delete:
      summary: Deletes an account contact relation. The ID of the account contact
        relation must be specified.
      description: Deletes an account contact relation. the id of the account contact
        relation must be specified..
      operationId: deleteRestAccountsContactRelationsAccountcontactrelation
      x-api-path-slug: restaccountscontact-relationsaccountcontactrelationid-delete
      parameters:
      - in: path
        name: accountContactRelationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Account
      - Contact
      - Relation
      - ""
      - ID
      - Of
      - Account
      - Contact
      - Relation
      - Must
      - Be
      - Specified
    get:
      summary: Gets an account contact releation. The ID of the account contact relation
        must be specified.
      description: Gets an account contact releation. the id of the account contact
        relation must be specified..
      operationId: getRestAccountsContactRelationsAccountcontactrelation
      x-api-path-slug: restaccountscontact-relationsaccountcontactrelationid-get
      parameters:
      - in: path
        name: accountContactRelationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Account
      - Contact
      - Releation
      - ""
      - ID
      - Of
      - Account
      - Contact
      - Relation
      - Must
      - Be
      - Specified
  /rest/accounts/contacts/classes:
    get:
      summary: List contact classes
      description: List contact classes.
      operationId: getRestAccountsContactsClasses
      x-api-path-slug: restaccountscontactsclasses-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Classes
  /rest/accounts/contacts/classes/{contactClassId}:
    get:
      summary: Get a contact class
      description: Gets a contact class. The ID of the contact class must be specified.
      operationId: getRestAccountsContactsClassesContactclass
      x-api-path-slug: restaccountscontactsclassescontactclassid-get
      parameters:
      - in: path
        name: contactClassId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Class
  /rest/accounts/contacts/contact_events:
    get:
      summary: List contact events
      description: Lists contact events.
      operationId: getRestAccountsContactsContactEvents
      x-api-path-slug: restaccountscontactscontact-events-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Events
    post:
      summary: Create a contact event
      description: Creates a contact event.
      operationId: postRestAccountsContactsContactEvents
      x-api-path-slug: restaccountscontactscontact-events-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/contact_events
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Event
  /rest/accounts/contacts/contact_events/{contactEventId}:
    delete:
      summary: Delete a contact event
      description: Deletes a contact event. The ID of the contact event must be specified.
      operationId: deleteRestAccountsContactsContactEventsContactevent
      x-api-path-slug: restaccountscontactscontact-eventscontacteventid-delete
      parameters:
      - in: path
        name: contactEventId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Event
    put:
      summary: Update a contact event
      description: Updates a contact event. The ID of the contact event must be specified.
      operationId: putRestAccountsContactsContactEventsContactevent
      x-api-path-slug: restaccountscontactscontact-eventscontacteventid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/contact_events/{contactEventId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactEventId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Event
  /rest/accounts/contacts/departments:
    get:
      summary: List contact departments
      description: List contact departments.
      operationId: getRestAccountsContactsDepartments
      x-api-path-slug: restaccountscontactsdepartments-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Departments
    post:
      summary: Create a contact department
      description: Create a contact department.
      operationId: postRestAccountsContactsDepartments
      x-api-path-slug: restaccountscontactsdepartments-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/departments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
  /rest/accounts/contacts/departments/{departmentId}:
    delete:
      summary: Delete a contact department
      description: Deletes a contact department. The ID of the department must be
        specified.
      operationId: deleteRestAccountsContactsDepartmentsDepartment
      x-api-path-slug: restaccountscontactsdepartmentsdepartmentid-delete
      parameters:
      - in: path
        name: departmentId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
    get:
      summary: Get a contact department
      description: Gets a contact department. The ID of the department must be specified.
      operationId: getRestAccountsContactsDepartmentsDepartment
      x-api-path-slug: restaccountscontactsdepartmentsdepartmentid-get
      parameters:
      - in: path
        name: departmentId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
    put:
      summary: Update a contact department
      description: Updates a contact department. The ID of the department must be
        specified.
      operationId: putRestAccountsContactsDepartmentsDepartment
      x-api-path-slug: restaccountscontactsdepartmentsdepartmentid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/departments/{departmentId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: departmentId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
  /rest/accounts/contacts/group_functions:
    post:
      summary: Apply selected group function options for given contact IDs
      description: Applies selected group function options for given contact IDs.
      operationId: postRestAccountsContactsGroupFunctions
      x-api-path-slug: restaccountscontactsgroup-functions-post
      parameters:
      - in: query
        name: addressLabelTemplate
        description: An address label template ID
      - in: query
        name: contactList
        description: A list of contact IDs
      - in: query
        name: emailTemplate
        description: An email template ID
      - in: query
        name: newsletter
        description: A newsletter folder ID
      responses:
        200:
          description: OK
      tags:
      - Apply
      - Selected
      - Group
      - Function
      - Optionsgiven
      - Contact
      - IDs
  /rest/accounts/contacts/option_sub_types:
    get:
      summary: List contact option sub-types
      description: List contact option sub-types.
      operationId: getRestAccountsContactsOptionSubTypes
      x-api-path-slug: restaccountscontactsoption-sub-types-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Option
      - Sub-types
    post:
      summary: Create a contact option sub-type
      description: Create a contact option sub-type.
      operationId: postRestAccountsContactsOptionSubTypes
      x-api-path-slug: restaccountscontactsoption-sub-types-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_sub_types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Sub-type
  /rest/accounts/contacts/option_sub_types/{optionSubTypeId}:
    delete:
      summary: Delete a contact option sub-type
      description: Deletes a contact option sub-type. The ID of the option sub-type
        must be specified.
      operationId: deleteRestAccountsContactsOptionSubTypesOptionsubtype
      x-api-path-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-delete
      parameters:
      - in: path
        name: optionSubTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Sub-type
    get:
      summary: Get a contact option sub-type
      description: Gets a contact option sub-type. The ID of the option sub-type must
        be specified.
      operationId: getRestAccountsContactsOptionSubTypesOptionsubtype
      x-api-path-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-get
      parameters:
      - in: path
        name: optionSubTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Sub-type
    put:
      summary: Update a contact option sub-type
      description: Updates a contact option sub-type. The ID of the option sub-type
        must be specified.
      operationId: putRestAccountsContactsOptionSubTypesOptionsubtype
      x-api-path-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_sub_types/{optionSubTypeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: optionSubTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Sub-type
  /rest/accounts/contacts/option_types:
    get:
      summary: List contact option types
      description: List contact option types.
      operationId: getRestAccountsContactsOptionTypes
      x-api-path-slug: restaccountscontactsoption-types-get
      parameters:
      - in: query
        name: with
        description: Lists possible option sub-types for each listed option if the
          parameter subTypes is set
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Option
      - Types
    post:
      summary: Create a contact option type
      description: Create a contact option type.
      operationId: postRestAccountsContactsOptionTypes
      x-api-path-slug: restaccountscontactsoption-types-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
  /rest/accounts/contacts/option_types/{optionTypeId}:
    delete:
      summary: Delete a contact option type
      description: Deletes a contact option type. The ID of the option type must be
        specified.
      operationId: deleteRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-delete
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
    get:
      summary: Get a contact option type
      description: Gets a contact option type. The ID of the option type must be specified.
      operationId: getRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-get
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
    put:
      summary: Update a contact option type
      description: Updates a contact option type. The ID of the option type must be
        specified.
      operationId: putRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_types/{optionTypeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
  /rest/accounts/contacts/options/{optionId}:
    delete:
      summary: Delete a contact option by the option ID
      description: Deletes a contact option. The ID of the option must be specified.
      operationId: deleteRestAccountsContactsOptionsOption
      x-api-path-slug: restaccountscontactsoptionsoptionid-delete
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Option
      - ID
    get:
      summary: Get a contact option by the option ID
      description: Gets a contact option. The ID of the option must be specified.
      operationId: getRestAccountsContactsOptionsOption
      x-api-path-slug: restaccountscontactsoptionsoptionid-get
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Option
      - ID
    put:
      summary: Update a contact option by the option ID
      description: Updates a contact option. The ID of the option must be specified.
      operationId: putRestAccountsContactsOptionsOption
      x-api-path-slug: restaccountscontactsoptionsoptionid-put
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Option
      - ID
  /rest/accounts/contacts/positions:
    get:
      summary: List contact positions
      description: List contact positions.
      operationId: getRestAccountsContactsPositions
      x-api-path-slug: restaccountscontactspositions-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Positions
    post:
      summary: Create a contact position
      description: Create a contact position.
      operationId: postRestAccountsContactsPositions
      x-api-path-slug: restaccountscontactspositions-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/positions
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Position
  /rest/accounts/contacts/positions/{positionId}:
    delete:
      summary: Delete a contact position
      description: Deletes a contact position. The ID of the position must be specified.
      operationId: deleteRestAccountsContactsPositionsPosition
      x-api-path-slug: restaccountscontactspositionspositionid-delete
      parameters:
      - in: path
        name: positionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Position
    get:
      summary: Get a contact position
      description: Gets a contact position. The ID of the position must be specified.
      operationId: getRestAccountsContactsPositionsPosition
      x-api-path-slug: restaccountscontactspositionspositionid-get
      parameters:
      - in: path
        name: positionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Position
    put:
      summary: Update a contact position
      description: Updates a contact position. The ID of the position must be specified.
      operationId: putRestAccountsContactsPositionsPosition
      x-api-path-slug: restaccountscontactspositionspositionid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/positions/{positionId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: positionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Position
  /rest/accounts/contacts/types:
    get:
      summary: List contact types
      description: List contact types.
      operationId: getRestAccountsContactsTypes
      x-api-path-slug: restaccountscontactstypes-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Types
    post:
      summary: Create a contact type
      description: Create a contact type.
      operationId: postRestAccountsContactsTypes
      x-api-path-slug: restaccountscontactstypes-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
  /rest/accounts/contacts/types/{typeId}:
    delete:
      summary: Delete a contact type
      description: Deletes a contact type. The ID of the contact type must be specified.
      operationId: deleteRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-delete
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
    get:
      summary: Get a contact type
      description: Gets a contact type. The ID of the contact type must be specified.
      operationId: getRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-get
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
    put:
      summary: Update a contact type
      description: Updates a contact type. The ID of the contact type must be specified.
      operationId: putRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/types/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
  /rest/accounts/contacts/{contactId}:
    delete:
      summary: Delete a contact
      description: Deletes a contact. The ID of the contact must be specified.
      operationId: deleteRestAccountsContactsContact
      x-api-path-slug: restaccountscontactscontactid-delete
      parameters:
      - in: query
        name: checkExistingOrders
        description: Flag that checks if the contact is linked to orders
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
    get:
      summary: Get a contact
      description: Gets a contact. The ID of the contact must be specified.
      operationId: getRestAccountsContactsContact
      x-api-path-slug: restaccountscontactscontactid-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: with
        description: Includes the specified contact information in the results
      responses:
        200:
          description: OK
      tags:
      - Contact
    put:
      summary: Update a contact
      description: Updates a contact. The ID of the contact must be specified.
      operationId: putRestAccountsContactsContact
      x-api-path-slug: restaccountscontactscontactid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/{contactId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
  /rest/accounts/contacts/{contactId}/access_data/new_password:
    put:
      summary: Send password link for a contact
      description: Sends an email to a contact with a link to change the password.
        The ID of the contact must be specified.
      operationId: putRestAccountsContactsContactAccessDataNewPassword
      x-api-path-slug: restaccountscontactscontactidaccess-datanew-password-put
      parameters:
      - in: path
        name: contactId
      - in: query
        name: password
        description: The new password
      responses:
        200:
          description: OK
      tags:
      - Send
      - Password
      - Linka
      - Contact
  /rest/accounts/contacts/{contactId}/access_data/set_password:
    put:
      summary: Update the password for a contact
      description: Updates the password for a contact. The ID of the contact must
        be specified.
      operationId: putRestAccountsContactsContactAccessDataSetPassword
      x-api-path-slug: restaccountscontactscontactidaccess-dataset-password-put
      parameters:
      - in: path
        name: contactId
      - in: query
        name: password
        description: The new password
      responses:
        200:
          description: OK
      tags:
      - Passworda
      - Contact
  /rest/accounts/contacts/{contactId}/access_data/unblock_user:
    put:
      summary: Unblock a contact
      description: Unblocks a contact to allow this contact to log in again. The ID
        of the contact must be specified.
      operationId: putRestAccountsContactsContactAccessDataUnblockUser
      x-api-path-slug: restaccountscontactscontactidaccess-dataunblock-user-put
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Unblock
      - Contact
  /rest/accounts/contacts/{contactId}/accounts:
    post:
      summary: Create an account for existing contact
      description: Creates an account for an existing contact. The ID of the contact
        must be specified.
      operationId: postRestAccountsContactsContactAccounts
      x-api-path-slug: restaccountscontactscontactidaccounts-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/{contactId}/accounts
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Accountexisting
      - Contact
  /rest/accounts/contacts/{contactId}/accounts/{accountId}:
    delete:
      summary: Delete an account of the contact
      description: Deletes an account of the contact. The ID of the contact and the
        ID of the account must be specified.
      operationId: deleteRestAccountsContactsContactAccountsAccount
      x-api-path-slug: restaccountscontactscontactidaccountsaccountid-delete
      parameters:
      - in: path
        name: accountId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Account
      - Of
      - Contact
    get:
      summary: Get an account of the contact
      description: Gets an account of the contact. The ID of the contact and the ID
        of the account must be specified.
      operationId: getRestAccountsContactsContactAccountsAccount
      x-api-path-slug: restaccountscontactscontactidaccountsaccountid-get
      parameters:
      - in: path
        name: accountId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Account
      - Of
      - Contact
  /rest/accounts/contacts/{contactId}/addresses:
    post:
      summary: Create an address for existing contact and type
      description: Creates an address. The ID of the contact must be specified.
      operationId: postRestAccountsContactsContactAddresses
      x-api-path-slug: restaccountscontactscontactidaddresses-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/{contactId}/addresses
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactId
      - in: query
        name: isPrimary
        description: Sets a contact address per address type as the primary address
      - in: query
        name: typeId
        description: The type ID of the address
      responses:
        200:
          description: OK
      tags:
      - Addressexisting
      - Contact
      - Type
  /rest/accounts/contacts/{contactId}/addresses/{addressId}:
    delete:
      summary: Delete an address of the contact
      description: Deletes an address of the contact. The ID of the contact and the
        ID of the address must be specified.
      operationId: deleteRestAccountsContactsContactAddressesAddress
      x-api-path-slug: restaccountscontactscontactidaddressesaddressid-delete
      parameters:
      - in: path
        name: addressId
      - in: path
        name: contactId
      - in: query
        name: typeId
        description: The type ID of the address
      responses:
        200:
          description: OK
      tags:
      - Address
      - Of
      - Contact
    put:
      summary: Update an address of the contact
      description: Updates an address of the contact. The ID of the contact and the
        ID of the address must be specified.
      operationId: putRestAccountsContactsContactAddressesAddress
      x-api-path-slug: restaccountscontactscontactidaddressesaddressid-put
      parameters:
      - in: path
        name: addressId
      - in: path
        name: contactId
      - in: query
        name: isPrimary
        description: Sets a contact address per address type as the primary address
      - in: query
        name: typeId
        description: The type ID of the address
      responses:
        200:
          description: OK
      tags:
      - Address
      - Of
      - Contact
  /rest/accounts/contacts/{contactId}/addresses/{addressId}/types/{addressTypeId}/primary:
    put:
      summary: Set a contact address per address type as the primary address
      description: Sets a contact address per address type as the primary address.
        The ID of the contact, the ID of the address and the ID of the address type
        must be specified. A primary address is also definable if you create or update
        a contact address.
      operationId: putRestAccountsContactsContactAddressesAddressTypesAddresstypePrimary
      x-api-path-slug: restaccountscontactscontactidaddressesaddressidtypesaddresstypeidprimary-put
      parameters:
      - in: path
        name: addressId
      - in: path
        name: addressTypeId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Set
      - Contact
      - Address
      - Per
      - Address
      - Type
      - As
      - Primary
      - Address
  /rest/accounts/contacts/{contactId}/addresses/{addressId}/types/{addressTypeId}/reset_primary:
    put:
      summary: Resets a contact primary address
      description: Resets a contact primary address. The ID of the contact, the ID
        of the address and the ID of the address type must be specified.
      operationId: putRestAccountsContactsContactAddressesAddressTypesAddresstypeResetPrimary
      x-api-path-slug: restaccountscontactscontactidaddressesaddressidtypesaddresstypeidreset-primary-put
      parameters:
      - in: path
        name: addressId
      - in: path
        name: addressTypeId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Resets
      - Contact
      - Primary
      - Address
  /rest/accounts/contacts/{contactId}/anonymize:
    put:
      summary: anonymize Contact
      description: anonymizes the given contact.
      operationId: putRestAccountsContactsContactAnonymize
      x-api-path-slug: restaccountscontactscontactidanonymize-put
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Anonymize
      - Contact
  /rest/accounts/contacts/{contactId}/contact_events:
    get:
      summary: List contact events by contact ID
      description: Lists contact events by contact ID. The ID of the contact must
        be specified.
      operationId: getRestAccountsContactsContactContactEvents
      x-api-path-slug: restaccountscontactscontactidcontact-events-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Events
      - By
      - Contact
      - ID
  /rest/accounts/contacts/{contactId}/document:
    get:
      summary: Get a single storage object from contact documents
      description: Get a single storage object from contact documents.
      operationId: getRestAccountsContactsContactDocument
      x-api-path-slug: restaccountscontactscontactiddocument-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key of the object to get from contact documents
      responses:
        200:
          description: OK
      tags:
      - Single
      - Storage
      - Object
      - From
      - Contact
      - Documents
    post:
      summary: Upload a document to contact directory
      description: Upload a document to contact directory.
      operationId: postRestAccountsContactsContactDocument
      x-api-path-slug: restaccountscontactscontactiddocument-post
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key for the file to upload
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Document
      - To
      - Contact
      - Directory
  /rest/accounts/contacts/{contactId}/documents:
    delete:
      summary: Delete files from contact documents
      description: Delete files from contact documents.
      operationId: deleteRestAccountsContactsContactDocuments
      x-api-path-slug: restaccountscontactscontactiddocuments-delete
      parameters:
      - in: path
        name: contactId
      - in: query
        name: keyList
        description: List of storage keys to delete
      responses:
        200:
          description: OK
      tags:
      - Files
      - From
      - Contact
      - Documents
    get:
      summary: List documents for a single contact
      description: List documents for a single contact.
      operationId: getRestAccountsContactsContactDocuments
      x-api-path-slug: restaccountscontactscontactiddocuments-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: continuationToken
        description: token from previous request to continue listing documents
      responses:
        200:
          description: OK
      tags:
      - List
      - Documentsa
      - Single
      - Contact
  /rest/accounts/contacts/{contactId}/options:
    delete:
      summary: Delete a contact option by the contact ID
      description: Deletes a contact option for an existing contact. The ID of the
        contact must be specified.
      operationId: deleteRestAccountsContactsContactOptions
      x-api-path-slug: restaccountscontactscontactidoptions-delete
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Contact
      - ID
    get:
      summary: List contact options by the contact ID
      description: Lists contact options. The ID of the contact must be specified.
      operationId: getRestAccountsContactsContactOptions
      x-api-path-slug: restaccountscontactscontactidoptions-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Options
      - By
      - Contact
      - ID
    post:
      summary: Create a contact option by the contact ID
      description: Creates a contact option for an existing contact. The ID of the
        contact must be specified.
      operationId: postRestAccountsContactsContactOptions
      x-api-path-slug: restaccountscontactscontactidoptions-post
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Contact
      - ID
    put:
      summary: Update a contact option by the contact ID
      description: Updates a contact option for an existing contact. The ID of the
        contact must be specified.
      operationId: putRestAccountsContactsContactOptions
      x-api-path-slug: restaccountscontactscontactidoptions-put
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Contact
      - ID
  /rest/accounts/contacts/{contactId}/options/validate:
    get:
      summary: Validate a contact option by a given value
      description: validates a contact option by a given value
      operationId: getRestAccountsContactsContactOptionsValate
      x-api-path-slug: restaccountscontactscontactidoptionsvalidate-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Validate
      - Contact
      - Option
      - By
      - Given
      - Value
  /rest/accounts/contacts/{contactId}/related_data:
    get:
      summary: Return all contact related data
      description: Returns all contact related data.
      operationId: getRestAccountsContactsContactRelatedData
      x-api-path-slug: restaccountscontactscontactidrelated-data-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Return
      - ""
      - Contact
      - Related
      - Data
  /rest/accounts/order_summaries/contacts/{contactId}:
    get:
      summary: Get an order summary by the contact ID
      description: Gets an order summary. The ID of the contact must be specified.
      operationId: getRestAccountsOrderSummariesContactsContact
      x-api-path-slug: restaccountsorder-summariescontactscontactid-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
      - By
      - Contact
      - ID
  /rest/boards/{boardId}/columns/{columnId}/tasks/{taskId}/references:
    post:
      summary: Creates a new reference from a given task to a contact or a ticket.
      description: Creates a new reference from a given task to a contact or a ticket..
      operationId: postRestBoardsBoardColumnsColumnTasksTaskReferences
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskidreferences-post
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: query
        name: referenceValue
        description: Reference type followed by foreign ID of the referenced object
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Reference
      - From
      - Given
      - Task
      - To
      - Contact
      - Ticket
  /rest/orders/contacts/{contactId}:
    get:
      summary: List orders of a contact
      description: Lists all orders of a contact. The ID of the contact must be specified.
      operationId: getRestOrdersContactsContact
      x-api-path-slug: restorderscontactscontactid-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: itemsPerPage
        description: The number of orders to be displayed per page
      - in: query
        name: page
        description: The page to get
      - in: query
        name: with
        description: Load additional relations for an order
      responses:
        200:
          description: OK
      tags:
      - List
      - Orders
      - Of
      - Contact
  /rest/orders/coupons/codes/contacts/{contactId}:
    get:
      summary: List redeemed coupon codes of a contact
      description: Lists the redeemed coupon codes of contact. The ID of the contact
        must be specified.
      operationId: getRestOrdersCouponsCodesContactsContact
      x-api-path-slug: restorderscouponscodescontactscontactid-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: itemsPerPage
        description: The number of coupons to be displayed per page
      - in: query
        name: page
        description: The page to get
      responses:
        200:
          description: OK
      tags:
      - List
      - Redeemed
      - Coupon
      - Codes
      - Of
      - Contact
  /rest/orders/{orderId}/contactWish:
    get:
      summary: Get a contact wish
      description: Gets the contact wish for an order. The ID of the order must be
        specified.
      operationId: getRestOrdersOrderContactwish
      x-api-path-slug: restordersorderidcontactwish-get
      parameters:
      - in: path
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Wish
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