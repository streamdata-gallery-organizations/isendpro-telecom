{
  "info": {
    "name": "API i Send Pro Retourne les SMS envoyés sur une période donnée",
    "_postman_id": "6fea5e94-7f01-4e04-be76-69169a70b7f4",
    "description": "Retourne les SMS envoyés sur une période donnée en fonction d'une date de début et d'une date de fin. \n\nLes dates sont au format YYYY-MM-DD hh:mm. \n\nLe fichier rapport de campagne est sous la forme d'un fichier zip + contenant un fichier csv contenant le détail des envois.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Campagne",
      "item": [
        {
          "id": "65a35888-c232-4e4d-9714-fa226df1ed7d",
          "name": "getCampagne",
          "request": {
            "url": "http://apirest.isendpro.com/cgi-bin/campagne?date_deb=%7B%7D&date_fin=%7B%7D&keyid=%7B%7D&rapportCampagne=%7B%7D",
            "method": "GET",
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
            "description": "Retourne les SMS envoyés sur une période donnée en fonction d'une date de début et d'une date de fin. \n\nLes dates sont au format YYYY-MM-DD hh:mm. \n\nLe fichier rapport de campagne est sous la forme d'un fichier zip + contenant un fichier csv contenant le détail des envois."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb0396db-f9c3-4b0f-ae8b-d21b4de98c2b"
            }
          ]
        }
      ]
    }
  ]
}