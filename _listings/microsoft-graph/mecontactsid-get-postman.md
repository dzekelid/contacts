{
  "info": {
    "name": "Microsoft Graph API Get Contact",
    "_postman_id": "7667b559-10b0-4e0a-8694-d4e5481dc40a",
    "description": "Get contact Retrieve the properties and relationships of a contact object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attachment",
      "item": [
        {
          "id": "afecdcd9-42bf-4f9f-9194-1408d19448ef",
          "name": "GetAttachment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36b12001-11ae-4bd3-ac61-33352a94a316"
            }
          ]
        },
        {
          "id": "582ac99b-eadb-472f-a675-12e562db9c82",
          "name": "GetAttachment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5ac6361-f56d-459c-a723-ce549c518e8b"
            }
          ]
        },
        {
          "id": "dcd3328c-d0b2-4b75-955f-c49774474f08",
          "name": "GetAttachment1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65b9b57a-dd8a-4f70-85e3-b3bedc062141"
            }
          ]
        },
        {
          "id": "d8146b2a-6ce3-41e0-ae40-9f748808ac92",
          "name": "GetAttachment2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendar/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb2047a6-db80-415d-99a2-ca6ec9aa3858"
            }
          ]
        },
        {
          "id": "d165d986-b7d4-4b70-9744-f0a60d7a8744",
          "name": "GetAttachment1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendar/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb006135-21fb-4b63-a7ce-231208b4a89e"
            }
          ]
        },
        {
          "id": "26889024-b1ab-47dd-a4bc-a8f5894e5ea5",
          "name": "GetAttachment3",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/calendar/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b0ef88e-6730-4312-989a-6cdf79905524"
            }
          ]
        },
        {
          "id": "f93f537b-7876-4518-9724-8d060440f5bc",
          "name": "GetAttachment4",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c8b02ce-79cc-400e-a985-69faefbbf8b8"
            }
          ]
        },
        {
          "id": "a2930489-24bd-436c-a827-71f5f833ae9e",
          "name": "GetAttachment2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad6a546b-2f56-4e42-8c81-6fc6d1287194"
            }
          ]
        },
        {
          "id": "7bcb6e1d-46a8-40a2-9363-a48e96cad2fa",
          "name": "GetAttachment5",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendargroup/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "122b765a-d426-4be4-ba5f-5a61849064e2"
            }
          ]
        },
        {
          "id": "c42418dc-c884-4cfb-9e1d-c676d8faf9f1",
          "name": "GetAttachment3",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendargroup/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34f06e02-9dc3-4d9f-9d17-b8b358442274"
            }
          ]
        },
        {
          "id": "51863518-aa12-4082-9b1e-7c0f421f43a9",
          "name": "GetAttachment6",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendargroups/:id/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2dac522-4522-413d-aee8-b59caeb3410c"
            }
          ]
        },
        {
          "id": "a9a7fae0-c8e4-4c52-a43f-020d5bb3d074",
          "name": "GetAttachment4",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendargroups/:id/calendars/:id/events/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4cb3d4e3-f214-45de-a9c3-fdc2d21554d4"
            }
          ]
        },
        {
          "id": "a7c4b179-3a1d-4b43-a844-43431d9bb2f6",
          "name": "GetAttachment7",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f20eca5d-b136-4134-9eb3-602a7ecfcfba"
            }
          ]
        },
        {
          "id": "b97c03c8-74b0-4e8d-a18c-1b0a8207de5d",
          "name": "GetAttachment5",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71041cef-27a3-45a9-9c2a-833f4941ac44"
            }
          ]
        },
        {
          "id": "eb82495d-b116-4eb6-b48a-46efe2721f19",
          "name": "GetAttachment8",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/mailFolders/:id/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e05d721d-96ab-430e-84a9-60b31151eb53"
            }
          ]
        },
        {
          "id": "6736fff8-a369-4f50-916a-20b6c57464cf",
          "name": "GetAttachment6",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/mailFolders/:id/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3187b5d4-a593-4e9d-b54e-8f38198fadb4"
            }
          ]
        },
        {
          "id": "4fb9ce49-f107-49d7-a3c1-13d9e5503377",
          "name": "GetAttachment9",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/threads/:id/posts/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "470b7f81-fb82-4408-8e59-a871e5fa30a8"
            }
          ]
        },
        {
          "id": "1af0cbab-7408-49f9-98d0-0bfefe41517b",
          "name": "GetAttachment10",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/conversations/:id/threads/:id/posts/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get attachment\nRead the properties and relationships of an attachment, attached to an event,\nmessage, or post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ee83045-6bae-49eb-8217-b9f445e61779"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "529d52f1-ef1f-44ca-a971-ed995dce072c",
          "name": "ListAttachments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/mailFolders/:id/childFolders/:id/.../messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List attachments Retrieve a list of attachment objects attached to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2dbbe127-4e43-46eb-ac3b-2691f813dc7f"
            }
          ]
        },
        {
          "id": "4b6fe9a3-ce15-4255-89ec-a206a724a265",
          "name": "ListAttachments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/mailFolders/:id/childFolders/:id/messages/:id/attachments/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List attachments Retrieve a list of attachment objects attached to a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e41ba2f-06a9-4021-b3a7-cc42d1dca94f"
            }
          ]
        },
        {
          "id": "4c238b0a-ff97-47df-8130-f6babd79383d",
          "name": "ListCalendarView",
          "request": {
            "url": "http://graph.microsoft.com/me/calendar/calendarView?endDateTime=endDateTime&startDateTime=startDateTime",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "application/json",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "Prefer",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69e4b597-69b3-474f-8721-9bb86dbb1e6d"
            }
          ]
        },
        {
          "id": "c81b96a0-b501-43da-bb00-2391caec36e3",
          "name": "ListCalendarView",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendar/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "499b5d8b-202c-4a38-ba02-d20ca9c8cc55"
            }
          ]
        },
        {
          "id": "eb308682-32c3-4ef4-87a1-592eb82121ef",
          "name": "ListCalendarView",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/calendar/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "24030407-1350-4b53-881b-ec4f1b12282f"
            }
          ]
        },
        {
          "id": "9c516acc-bc84-45d0-8e96-4817fdd5fc1e",
          "name": "ListCalendarView",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendars/:id/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "application/json",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "Prefer",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b31a1e4f-fa06-4822-9552-202eaa69be5e"
            }
          ]
        },
        {
          "id": "01861a2f-b44c-434e-8363-85dd05bd05da",
          "name": "ListCalendarView",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendars/:id/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "application/json",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "Prefer",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51339d8f-a715-4a2b-97fb-553b84293d88"
            }
          ]
        },
        {
          "id": "10ad2652-80f6-4613-ae55-be38e694eaa4",
          "name": "ListCalendarView1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendarGroup/calendars/:id/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "application/json",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "Prefer",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61106980-6b17-4728-9b6b-82bad837c870"
            }
          ]
        },
        {
          "id": "897c24ec-9cd7-423a-885d-74ff32422542",
          "name": "ListCalendarView1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendarGroup/calendars/:id/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "application/json",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "Prefer",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b56fc24b-08b3-4f6f-8c9d-c4de59dbcaf3"
            }
          ]
        },
        {
          "id": "ea04ddde-323f-471d-b2e8-7323a208e81f",
          "name": "ListCalendarView2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendarGroups/:id/calendars/:id/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "application/json",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "Prefer",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a42ff88-2ce4-462d-aefb-72f6d383a0c7"
            }
          ]
        },
        {
          "id": "e54f49b2-910f-4980-9fd6-f2b9d9f1eb61",
          "name": "ListCalendarView2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendarGroups/:id/calendars/:id/calendarView"
              ],
              "query": [
                {
                  "key": "endDateTime",
                  "value": "endDateTime",
                  "disabled": false
                },
                {
                  "key": "startDateTime",
                  "value": "startDateTime",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "application/json",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "Prefer",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendarView\nGet the occurrences, exceptions, and single instances of events in a calendar view defined by a time range,\nfrom the default calendar (../me/calendarview) of a user or group, or some other calendar of the user's."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ccc5c7f7-9c57-49ec-b6e6-86b0cd64bf39"
            }
          ]
        },
        {
          "id": "30e36987-b04d-4e77-b90f-042d6c47c991",
          "name": "ListEvents",
          "request": {
            "url": "http://graph.microsoft.com/me/calendar/events",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              },
              {
                "key": "Prefer: outlook.timezone",
                "value": "Prefer: outlook.timezone",
                "description": "The default time zone for events in the response",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of events in a calendar.  The list contains single instance meetings and series masters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2aef443b-1a25-4a1e-be4e-45e5f914db5c"
            }
          ]
        },
        {
          "id": "ada323b9-9a78-42ad-afdf-46f98786cef1",
          "name": "ListEvents",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendar/events"
              ],
              "variable": [
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              },
              {
                "key": "Prefer: outlook.timezone",
                "value": "Prefer: outlook.timezone",
                "description": "The default time zone for events in the response",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of events in a calendar.  The list contains single instance meetings and series masters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8fe1a43-0bde-4853-bfb1-c8509916171d"
            }
          ]
        },
        {
          "id": "a62b57a9-ab59-4a5b-a3dc-f2d4c4444620",
          "name": "ListEvents",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "groups/:id/calendar/events"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of event objects."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf81381a-9fd5-4988-828a-edf296e7e71d"
            }
          ]
        },
        {
          "id": "23f68850-692d-4f94-9b8b-7d6897323e3f",
          "name": "ListEvents",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendars/:id/events"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              },
              {
                "key": "Prefer: outlook.timezone",
                "value": "Prefer: outlook.timezone",
                "description": "The default time zone for events in the response",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of events in a calendar.  The list contains single instance meetings and series masters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b497414e-63ad-424f-9b7e-463962ff3cf2"
            }
          ]
        },
        {
          "id": "baa8484e-de7d-4068-9394-791fe80c75d3",
          "name": "ListEvents",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendars/:id/events"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              },
              {
                "key": "Prefer: outlook.timezone",
                "value": "Prefer: outlook.timezone",
                "description": "The default time zone for events in the response",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of events in a calendar.  The list contains single instance meetings and series masters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09b7c9aa-013c-4686-bf43-7c1fc3703f03"
            }
          ]
        },
        {
          "id": "3e6b9466-7648-4339-aa74-ece97993954b",
          "name": "ListEvents1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendarGroup/calendars/:id/events"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              },
              {
                "key": "Prefer: outlook.timezone",
                "value": "Prefer: outlook.timezone",
                "description": "The default time zone for events in the response",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of events in a calendar.  The list contains single instance meetings and series masters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78c27060-d07c-41be-910d-c87394754e79"
            }
          ]
        },
        {
          "id": "ba3adefc-f407-470c-b2b0-bd71543c16e7",
          "name": "ListEvents1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendarGroup/calendars/:id/events"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              },
              {
                "key": "Prefer: outlook.timezone",
                "value": "Prefer: outlook.timezone",
                "description": "The default time zone for events in the response",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of events in a calendar.  The list contains single instance meetings and series masters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75752c87-0507-4fff-9c4e-e6a81b715716"
            }
          ]
        },
        {
          "id": "abda9bb5-73b7-4078-929d-ac8de3886b60",
          "name": "ListEvents2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendarGroups/:id/calendars/:id/events"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              },
              {
                "key": "Prefer: outlook.timezone",
                "value": "Prefer: outlook.timezone",
                "description": "The default time zone for events in the response",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of events in a calendar.  The list contains single instance meetings and series masters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d92c5d9-2506-4675-99e8-011852082ca3"
            }
          ]
        },
        {
          "id": "56df5103-a208-467e-8b48-751220539bd6",
          "name": "ListEvents2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendarGroups/:id/calendars/:id/events"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                },
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Prefer",
                "value": "{}",
                "description": "outlook",
                "disabled": false
              },
              {
                "key": "Prefer: outlook.timezone",
                "value": "Prefer: outlook.timezone",
                "description": "The default time zone for events in the response",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List events Retrieve a list of events in a calendar.  The list contains single instance meetings and series masters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01989402-505f-4f4d-97fb-4060d19b17ab"
            }
          ]
        },
        {
          "id": "808fb83c-2790-4c73-9a76-03fcc9974063",
          "name": "ListCalendars",
          "request": {
            "url": "http://graph.microsoft.com/me/calendarGroup/calendars",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendars Retrieve a list of calendars belonging to a calendar group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcac230c-50ca-4a8f-aa47-d1251c7d048c"
            }
          ]
        },
        {
          "id": "57b40ca1-39d1-4d45-ab05-42ff20cfad17",
          "name": "ListCalendars",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendarGroup/calendars"
              ],
              "variable": [
                {
                  "id": "id | userPrincipalName",
                  "value": "id | userPrincipalName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "application/json",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendars Retrieve a list of calendars belonging to a calendar group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d01daf5b-b129-4c29-ac0a-2a872b043283"
            }
          ]
        },
        {
          "id": "e7f76e8e-971c-4fb1-bfb6-fcaa35b9af4a",
          "name": "ListCalendars",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "me/calendarGroups/:id/calendars"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List calendars Retrieve a list of calendars belonging to a calendar group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "515c243c-e60f-41cc-bfd6-38d157990505"
            }
          ]
        },
        {
          "id": "8d9375dc-05f0-4d38-8828-32e571df813a",
          "name": "ListCalendars",
          "request": {
            "url": {
              "protocol": "http",
              "host": "graph.microsoft.com",
              "path": [
                "users/:id | userPrincipalName/calendarGroups/:id/calendars"
              ],
              "variable": [
                {
                  "