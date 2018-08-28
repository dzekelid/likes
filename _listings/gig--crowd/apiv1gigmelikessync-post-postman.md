{
  "info": {
    "name": "GIGANDCROWD Post Gigme Likes Sync",
    "_postman_id": "94e73181-cf90-4be4-8733-f484f72e94b8",
    "description": "Post gigme likes sync.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Gigme",
      "item": [
        {
          "id": "fb202c85-40fc-470f-b533-f2edaba370ae",
          "name": "postApiV1GigmeLikesSync",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/gigme/likes/sync",
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Post gigme likes sync."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df0305c9-57a1-45df-850e-0a26535d4262"
            }
          ]
        }
      ]
    }
  ]
}