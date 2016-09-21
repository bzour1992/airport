# Airport

• Installing via Composer.

• Import database.

• Login Information: admin / 123456
  

Examples for JSON format:

http://localhost/advanced/frontend/web/site/read?id=11

or 

http://localhost/advanced/frontend/web/site/read?id=22

Sample for data structure:

{
    "ok": true,
    "message": "Successful",
    "airport": {
        "id": 1,
        "airport_code": "11",
        "airport_name": "Aliaa Airport",
        "country": "jo",
        "city": "Amman"
    }
}
