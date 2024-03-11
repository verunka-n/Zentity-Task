# Zentity-Task

This repository contains a Postman collection for interacting with Veronika's Books API.

## Endpoints:

### Get All Books
**GET** `/books/{{bookId}}`
- Expected Response: 200

### Get Book by ID
**GET** `/books/{{bookId}}`
- Expected Response: 200

### Get Book by Author Name
**GET** `/books?author={{authorFirstName}}%20{{authorLastName}}`
- Expected Response: 200

### Create Book
**POST** `/books`
- Expected Response: 201

### Update Book
**PUT** `/books/{{bookId}}`
- Expected Response: 200

### Delete Book
**DELETE** `/books/{{bookId}}`
- Expected Response: 204  

## Collection Link:
[Veronika's Books](https://bold-escape-565694.postman.co/workspace/test~c7c077cd-cf3a-435c-bc4d-8f93d51f7f71/collection/24180628-9ee57493-ff29-4000-abe8-a0dca3f16605?action=share&creator=24180628&active-environment=24180628-a573c736-218f-41c5-a60e-5d970c49bbae)
