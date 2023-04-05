Method	Url	Role Privilege	Action
GET	http://localhost:8080/api/v1/movie	ALL	Get all movie
GET	http://localhost:8080/api/v1/movie/{id}	ALL	Get movie by id

POST	http://localhost:8080/api/v1/movie	ADMIN	Create movie
POST	http://localhost:8080/api/v1/movie/{id}	ADMIN	Update movie by id

DELETE	http://localhost:8080/api/v1/movie/{id}/quote	ADMIN	Delete movie by id with quote
