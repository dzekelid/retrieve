{
  "info": {
    "name": "Dyn Retrieve Suppression Count",
    "_postman_id": "adb1c1ad-bbac-4d67-90cc-c046051fc03e",
    "description": "Retrieving the count of Email addresses on the suppression list",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Retrieve",
      "item": [
        {
          "id": "33ea6a39-0439-43f3-993e-dc6b0873aa63",
          "name": "getAccounts",
          "request": {
            "url": "http://example.com/api/accounts?apikey=%7B%7D&startindex=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving a list of up to 25 Email Sub-Accounts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e0c9ec27-132c-49cc-b8d3-98853f92bbc7"
            }
          ]
        },
        {
          "id": "98b95e68-96e1-41f2-b02d-57ce2a93dc66",
          "name": "getRecipientsStatus",
          "request": {
            "url": "http://example.com/api/recipients/status?apikey=%7B%7D&emailaddress=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve Recipient(s) Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a0badec-0c3a-4493-8dae-e29e9e8f1b97"
            }
          ]
        },
        {
          "id": "aabe7105-3153-4946-b87d-8d27ff4723ab",
          "name": "getReportsBounces",
          "request": {
            "url": "http://example.com/api/reports/bounces?apikey=%7B%7D&bounce_code - Indicates the code associated with the bounced Email.=%7B%7D&bounce_code_id - The numeric code determined by the bounce processor.=%7B%7D&bounce_rule - Indicates the rule that caused this email to bounce.=%7B%7D&bounce_type=%7B%7D&bounce_type_id - Indicates whether the bounce type is a hard or soft bounce.nValid Values:n1 - Hard Bouncen2 - Soft Bounce=%7B%7D&emailaddress=%7B%7D&endtime=%7B%7D&noheaders=%7B%7D&sender=%7B%7D&sender_id=%7B%7D&startindex=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving the Email SPAM Complaints"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58e059e4-b8d3-4b18-849c-f4f90ae065e2"
            }
          ]
        },
        {
          "id": "88483999-64fe-4acf-ac82-64836a824906",
          "name": "getReportsBouncesCount",
          "request": {
            "url": "http://example.com/api/reports/bounces/count?apikey=%7B%7D&endtime=%7B%7D&sender=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving a total count of Email bounces using the API requires specific syntax for the REST API."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "518895b4-1b36-4ee3-9d81-de23cd3ee058"
            }
          ]
        },
        {
          "id": "2ac65d00-565d-4765-9765-73fcaefee3c0",
          "name": "getReportsClicksCount",
          "request": {
            "url": "http://example.com/api/reports/clicks/count?apikey=%7B%7D&domainu00a0=%7B%7D&emailaddress=%7B%7D&endtime=%7B%7D&sender=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving a total of Email links clicked"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3a3b6cd-1e61-4187-bbe4-d15db538fe31"
            }
          ]
        },
        {
          "id": "3755c4b2-c9bc-47e8-b3c7-d012c2e30548",
          "name": "getReportsClicksCountUnique",
          "request": {
            "url": "http://example.com/api/reports/clicks/count/unique?apikey=%7B%7D&domainu00a0=%7B%7D&emailaddress=%7B%7D&endtime=%7B%7D&sender=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving a total of Email links clicked"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "52c8f4cc-24ac-49ce-b268-7c31f79d969d"
            }
          ]
        },
        {
          "id": "72abcd89-be19-4647-80a5-4d6db34bc8ad",
          "name": "getReportsComplaints",
          "request": {
            "url": "http://example.com/api/reports/complaints?apikey=%7B%7D&endtime=%7B%7D&sender=%7B%7D&startindex=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve Email SPAM Complaints"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c9f0a3c-3308-4d5e-94ad-cb3e20a5df97"
            }
          ]
        },
        {
          "id": "4f3eb13c-55da-4180-b8c7-6932054a853c",
          "name": "getReportsComplaintsCount",
          "request": {
            "url": "http://example.com/api/reports/complaints/count?apikey=%7B%7D&endtime=%7B%7D&starttime=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving a total count of Email complaints"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f6d7ff9-b63f-4008-b246-9f50960ccbda"
            }
          ]
        },
        {
          "id": "83185da0-287b-438d-a6e1-1195bde6a2f5",
          "name": "getReportsDelivered",
          "request": {
            "url": "http://example.com/api/reports/delivered?apikey=%7B%7D&endtime=%7B%7D&sender=%7B%7D&startindex=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve Emails Delivered"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e376ba47-f239-4d12-9210-d4e3ddd865c5"
            }
          ]
        },
        {
          "id": "656890e2-d2fc-4c10-8dbb-075e492aa588",
          "name": "getReportsDeliveredCount",
          "request": {
            "url": "http://example.com/api/reports/delivered/count?apikey=%7B%7D&endtime=%7B%7D&sender=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve Count of Emails Delivered"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b21e4b6-7cb5-47eb-8471-9ff1c62e9be4"
            }
          ]
        },
        {
          "id": "cc6d5e8f-5912-469a-a0b5-f825ea30c220",
          "name": "getReportsIssues",
          "request": {
            "url": "http://example.com/api/reports/issues?apikey=%7B%7D&emailaddress=%7B%7D&endtime=%7B%7D&sender=%7B%7D&sender_id=%7B%7D&startindex=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve Email Issues"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b15ebca-7f16-44e9-b505-0ef5c20db81b"
            }
          ]
        },
        {
          "id": "28000aba-6650-41c3-811b-07c7508dec42",
          "name": "getReportsIssuesCount",
          "request": {
            "url": "http://example.com/api/reports/issues/count?apikey=%7B%7D&endtime=%7B%7D&starttime=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving a total count of Email issues"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6927fb8b-d66f-4c4b-804b-3ac91f245577"
            }
          ]
        },
        {
          "id": "5d9af844-69fa-41f2-b638-72d92ac7d89d",
          "name": "getReportsOpensCountUnique",
          "request": {
            "url": "http://example.com/api/reports/opens/count/unique?apikey=%7B%7D&emailaddress=%7B%7D&endtime=%7B%7D&sender=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns total number of unique opens for the specified account for the specified date range. Including a date range is highly recommended."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1104eda-9b2e-4223-8329-cbcd1c322cb5"
            }
          ]
        },
        {
          "id": "eb4f0cf6-2195-40fc-bc7d-b1ab33635e10",
          "name": "getReportsSent",
          "request": {
            "url": "http://example.com/api/reports/sent?apikey=%7B%7D&endtime=%7B%7D&sender=%7B%7D&startindex=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve Emails Sent"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "317c2a7e-1b4d-427d-8797-2f95b7f7ae2c"
            }
          ]
        },
        {
          "id": "e57206bb-ae1c-48be-bad5-db0e4cffc4dd",
          "name": "getReportsSentCount",
          "request": {
            "url": "http://example.com/api/reports/sent/count?apikey=%7B%7D&endtime=%7B%7D&sender=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve Count of Emails Sent"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d293e7c-1941-4cd3-a305-32439b46194b"
            }
          ]
        },
        {
          "id": "72462b64-a3d2-44e0-b822-4e2be6bfe3b8",
          "name": "getSuppressions",
          "request": {
            "url": "http://example.com/api/suppressions?apikey=%7B%7D&startdate=%7B%7D&startindex=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving a list of Email addresses on the suppression list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f523613-9809-4a2a-8d4e-c50d13979ed5"
            }
          ]
        },
        {
          "id": "14ae7e50-9381-4b64-8f51-8843ef50d56e",
          "name": "getSuppressionsCount",
          "request": {
            "url": "http://example.com/api/suppressions/count?apikey=%7B%7D&enddate=%7B%7D&startdate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving the count of Email addresses on the suppression list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f35380f1-7128-46cb-8645-877444e83da1"
            }
          ]
        }
      ]
    },
    {
      "name": "Updating.Email",
      "item": [
        {
          "id": "039ef427-1c64-47db-af8d-40f162c22df8",
          "name": "putAccounts",
          "request": {
            "url": "http://example.com/api/accounts?address=%7B%7D&apikey=%7B%7D&bounceurl=%7B%7D&city=%7B%7D&companyname=%7B%7D&country=%7B%7D&generatenewapikey=%7B%7D&password=%7B%7D&phone=%7B%7D&spamurl=%7B%7D&state=%7B%7D&timezone=%7B%7D&tracklinks=%7B%7D&trackopens=%7B%7D&trackunsubscribes=%7B%7D&unsubscribeurl=%7B%7D&username=%7B%7D&zipcode=%7B%7D",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updating an Email Sub-Account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "008b57ef-1b84-4eb8-a0d7-54d9a30a656e"
            }
          ]
        }
      ]
    },
    {
      "name": "Create.Email",
      "item": [
        {
          "id": "0a68cc17-01d7-43e5-8ab7-90c83543cc94",
          "name": "postAccounts",
          "request": {
            "url": "http://example.com/api/accounts?address=%7B%7D&apikey=%7B%7D&bounceurl=%7B%7D&city=%7B%7D&companyname=%7B%7D&country=%7B%7D&generatenewapikey=%7B%7D&password=%7B%7D&phone=%7B%7D&spamurl=%7B%7D&state=%7B%7D&timezone=%7B%7D&tracklinks=%7B%7D&trackopens=%7B%7D&trackunsubscribes=%7B%7D&username=%7B%7D&zipcode=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creating an Email Sub-Account using the API requires specific syntax for the REST API."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ed80868-8077-4904-b00c-f60d68b55c74"
            }
          ]
        }
      ]
    },
    {
      "name": "Deleting.Email",
      "item": [
        {
          "id": "99790e5a-d157-4a6a-b576-70811d780efc",
          "name": "postAccountsDelete",
          "request": {
            "url": "http://example.com/api/accounts/delete?apikey=%7B%7D&username=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deleting an Email Sub-Account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b9f0612-0610-4385-b2a1-1246d913bc0c"
            }
          ]
        }
      ]
    },
    {
      "name": ".Email",
      "item": [
        {
          "id": "875ab06b-04a1-4677-bb25-c2e8010e6512",
          "name": "getOpensCount",
          "request": {
            "url": "http://example.com/api/opens/count?apikey=%7B%7D&emailaddress=%7B%7D&endtime=%7B%7D&sender=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns total number of opens for the specified account for the specified date range. Including a date range is highly recommended."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d81a4f45-8f6f-45b8-b763-fef1fe41df84"
            }
          ]
        },
        {
          "id": "89ef1709-4d2a-47f9-aefb-36cb4426c60f",
          "name": "postSuppressions",
          "request": {
            "url": "http://example.com/api/suppressions?apikey=%7B%7D&emailaddress=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adding one or more recipients to the suppression list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b072f43-6aa8-48de-adb7-200eefbe953d"
            }
          ]
        }
      ]
    },
    {
      "name": "Activate",
      "item": [
        {
          "id": "2220df70-4440-4b7e-8a0b-a437922dc7a0",
          "name": "postRecipientsActivate",
          "request": {
            "url": "http://example.com/api/recipients/activate?apikey=%7B%7D&emailaddress=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Activating a specified Recipientu2019s status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6848b519-070e-4b59-89f6-d2973045195b"
            }
          ]
        }
      ]
    },
    {
      "name": "Reports",
      "item": [
        {
          "id": "3fa63561-a1ff-4305-a59f-d52b4f22985a",
          "name": "getReportsClicks",
          "request": {
            "url": "http://example.com/api/reports/clicks?apikey=%7B%7D&emailaddress=%7B%7D&endtime=%7B%7D&sender=%7B%7D&startindex=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of links clicked for the specified account during the specified date range. Including a date range is highly recommended."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b895977-03ee-4f18-96dc-5553ae1f35c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Unique",
      "item": [
        {
          "id": "84211924-e05b-4f9e-b611-90fb951152d3",
          "name": "getReportsClicksUnique",
          "request": {
            "url": "http://example.com/api/reports/clicks/unique?apikey=%7B%7D&emailaddress=%7B%7D&endtime=%7B%7D&sender=%7B%7D&startindex=%7B%7D&starttime=%7B%7D&[X-HeaderName]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of unique links clicked for the specified account during the specified date range. Including a date range is highly recommended."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7fc92e87-c317-49db-a470-af2811f9b431"
            }
          ]
        }
      ]
    },
    {
      "name": "Send",
      "item": [
        {
          "id": "9b1d002c-6d72-4034-a2f2-85232bd1a1d7",
          "name": "postSend",
          "request": {
            "url": "http://example.com/api/send?apikey=%7B%7D&bcc=%7B%7D&bodyhtml=%7B%7D&bodytext=%7B%7D&cc=%7B%7D&comments=%7B%7D&from=%7B%7D&importance=%7B%7D&inreplyto=%7B%7D&keywords=%7B%7D&messageid=%7B%7D&priority=%7B%7D&references=%7B%7D&replyby=%7B%7D&replyto=%7B%7D&resent-date=%7B%7D&resent-from=%7B%7D&resent-messageid=%7B%7D&resent-replyto=%7B%7D&resent-sender=%7B%7D&sender=%7B%7D&sensitivity=%7B%7D&subject=%7B%7D&to=%7B%7D&xheaders=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Sending Email"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf03afd6-8f20-443c-bd01-3e23f52f2ddf"
            }
          ]
        }
      ]
    }
  ]
}