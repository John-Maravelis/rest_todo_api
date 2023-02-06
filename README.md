# This is a Todo list RESTful API for the purposes of the university class "SaaS".

## The project is installed on [todos_api](https://www.google.com "click me")

TDD is used and the tests are checked with [httpie](https://httpie.io/ "httpie").
The API is documented using openapi [Swagger](https://swagger.io/ "Swagger")

### The project will expose the following api endpoints with their corresponding functionality.
| Endpoint | Functionality |
| ------ | ------ |
| POST /signup | Signup |
| POST /auth/login | Login |
| GET /auth/logout | Logout |
| GET /todos | List all todos and todo items |
| POST /todos | Create a new todo |
| GET /todos/:id | Get a todo |
| PUT /todos/:id | Update a todo |
| DELETE /todos/:id | Delete a todo and its items |
| GET /todos/:id/items | Get a todo item |
| POST /todos/:id/items | Create a new todo item |
| PUT /todos/:id/items | Update a todo item |
| DELETE /todos/:id/items | Delete a todo item |

