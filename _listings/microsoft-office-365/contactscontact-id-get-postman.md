{
  "info": {
    "name": "Microsoft Office 365 Get Contacts Contact",
    "_postman_id": "212d824f-77f1-4560-8a59-2a8030caf6f5",
    "description": "You can retrieve information about a specific contact by usi...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "contacts",
      "item": [
        {
          "id": "13607920-b4f8-4fee-86f5-fa2c7eff3486",
          "name": "getContactsContact",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "Contacts:contact_id"
              ],
              "variable": [
                {
                  "id": "contact_id",
                  "value": "contact_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "You can retrieve information about a specific contact by usi"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d69dfb8-0c8c-4b59-a643-0f68cd8aef11"
            }
          ]
        }
      ]
    }
  ]
}