# flask-rest-api
## Before run app create kafka topic with the name "log".
## Dashboard Address
### http://127.0.0.1:5000/dashapp/
## ENDPOINTS
#### GET http://127.0.0.1:5000/books/
#### POST http://127.0.0.1:5000/books/
##### Example POST request:
{
    "title": "Somehow I manage",
    "author": "Michael SCOTT"
}
#### PUT http://127.0.0.1:5000/books/id
#### DELETE http://127.0.0.1:5000/books/id
