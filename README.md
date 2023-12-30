
# RESTful API with Go and PostgreSQL
This is a simple RESTful API implemented in Go that interacts with a PostgreSQL database. The API provides basic CRUD operations (Create, Read, Update, Delete) for managing user information. the app is dockerized using docker

# Prerequisites
1. Go installed on your machine
2. PostgreSQL database
3. Docker installed

# Getting Started
#### Clone the repository:
```bash
git clone https://github.com/MohamedAboMousallam/go-live.git

cd go-live
```

#### Set up the PostgreSQL database and configure the connection details.
 
#### Install dependencies:

```bash
go get -u github.com/gorilla/mux

go get -u github.com/lib/pq
```

## API Endpoints
#### Get all users
```http
GET /api/go/users
```
#### Get a user by ID
```http
GET /api/go/users/{id}
```
#### Create a new user
```http
POST /api/go/users
``` 
#### Update a user by id
```http
PUT /api/go/users{id}
``` 
#### Delete an existing user by id
```http
DELETE /api/go/users{id}
``` 
