POSTMAN API Documentation
-------------------------

1. Get Files Endpoint

- **Endpoint:** `GET /`

Request

GET http://localhost:3000/

Response

{
    "message": "File Write Success",
    "dateTime": "2023-12-01T14:16:09.791Z"
}

http
status 200 OK
-----------------------------------------------

2. Create File Endpoint

- **Endpoint:** `POST /create-file`

Request

POST http://localhost:3000/create-file

Body -> raw -> JSON

{
  "content": "This is the content of the file."
}


Response

{
    "message": "File Write Success",
    "fileName": "dateTime_post.txt",
    "dateTime": "2023-12-01T14:20:29.368Z"
}

http
status 200 OK
File created successfully
-------------------------------------------------------
