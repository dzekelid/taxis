{
  "info": {
    "name": "Microsoft Graph API Update Chartaxis",
    "_postman_id": "5807bf91-d470-4ce4-8f53-9bc09ca66278",
    "description": "Update chartaxis Update the properties of chartaxis object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chartaxis",
      "item": [
        {
          "id": "1d6cf30d-bc1e-491e-bba8-5dfba9a42257",
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
              "id": "476126f3-a777-47d4-ab2d-b0b3a52186f8"
            }
          ]
        }
      ]
    }
  ]
}