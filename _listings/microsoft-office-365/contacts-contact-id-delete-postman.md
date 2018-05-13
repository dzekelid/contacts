{
  "info": {
    "name": "Microsoft Office 365 Delete Contacts Contact",
    "_postman_id": "8051b53d-52d9-4a25-b6f9-4c6ac86fe6b3",
    "description": "You can delete a contact by simply sending a DELETE request ...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "contacts",
      "item": [
        {
          "id": "927c4a12-cb86-4dd5-bd5c-5c354def98de",
          "name": "deleteContactsContact",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "You can delete a contact by simply sending a DELETE request "
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be1b1dfc-b5f0-43ea-9515-88fa72006a7d"
            }
          ]
        }
      ]
    }
  ]
}