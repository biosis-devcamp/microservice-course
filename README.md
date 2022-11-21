# Microservice Course

## Endpoints

#### Save Course

````
POST /api/course HTTP/1.1
Host: localhost:7001
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleXBhc3N3b3JkIQ==
Content-Type: application/json

{
    "title": "test-course-title",
    "subtitle": "test-course-subtitle",
    "price": 10
}
````

#### Get Courses

````
GET /api/course HTTP/1.1
Host: localhost:7001
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleXBhc3N3b3JkIQ==
````

#### Delete Course

````
DELETE /api/course/2 HTTP/1.1
Host: localhost:7001
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleXBhc3N3b3JkIQ==
````
