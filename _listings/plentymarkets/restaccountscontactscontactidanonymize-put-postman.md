{
  "info": {
    "name": "Plentymarkets anonymize Contact",
    "_postman_id": "eceec5fb-a300-40f6-8d42-24f45e9274ab",
    "description": "anonymizes the given contact.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Anonymize",
      "item": [
        {
          "id": "84186704-7eb0-45cf-b878-10cf43594b6b",
          "name": "putRestAccountsContactsContactAnonymize",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/accounts/contacts/:contactId/anonymize"
              ],
              "variable": [
                {
                  "id": "contactId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "anonymizes the given contact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9289757-6ffc-4b53-9c3f-39702f99635d"
            }
          ]
        }
      ]
    }
  ]
}