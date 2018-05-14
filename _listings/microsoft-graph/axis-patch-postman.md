{
  "info": {
    "name": "Microsoft Graph API Update Chartaxis",
    "_postman_id": "055d490f-04c1-4253-9520-f4fb8e21b3a1",
    "description": "Update chartaxis Update the properties of chartaxis object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chartaxis",
      "item": [
        {
          "id": "307c94f2-e201-4ee9-86bc-e413a1b5d8a5",
          "name": "UpdateChartaxis",
          "request": {
            "url": "http://graph.microsoft.com/axis",
            "method": "PATCH",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Update chartaxis Update the properties of chartaxis object"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "46d0b5f1-b0c9-4217-b321-6a17f8513351"
            }
          ]
        }
      ]
    }
  ]
}