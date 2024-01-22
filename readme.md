# Golang CRUD GIN
## My App Name
Learn CRUD with GIN & Gorm

## Server
### To get started with server, install all dependency using `go get .`, then run
- ### setup your database or if you want to use docker compose run `docker compose up`
- ### run the server using command `go run main.go`

### Server tech stacks
- golang
- gin
- gorm

### List of basic routes:

| Route  | HTTP | Headers(s) | Body | Description         |
| ------ | ---- | ---------- | ---- | ------------------- |
| http://localhost:8888/api/tags   | POST  | None    | {name:string} | create tags
| http://localhost:8888/api/tags   | GET  | None     | none | find all tags
| http://localhost:8888/api/tags/:id   | GET  | None  | none | find tags by id
| http://localhost:8888/api/tags/:id   | PUT  | None     | {name:string, password:string} | update tags by id
| http://localhost:8888/api/tags/:id   | DELETE  | None  | none | delete tags by id