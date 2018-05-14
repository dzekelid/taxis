{
  "info": {
    "name": "Microsoft Graph API Update Chartaxis",
    "_postman_id": "788959d7-93a1-48d1-ad36-d50a2cb23ef5",
    "description": "Update chartaxis Update the properties of chartaxis object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chartaxis",
      "item": [
        {
          "id": "e9066060-a281-4cad-9f55-0a21936c9f6a",
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
              "id": "0a2705e9-4d74-474a-9d81-67dff59ddf0f"
            }
          ]
        }
      ]
    }
  ]
}