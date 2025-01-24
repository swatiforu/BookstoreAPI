# BookstoreAPI
A learning project for FastAPI

| Method | Route                      | Functionality                      | Access    |
|--------|----------------------------|------------------------------------|-----------|
| GET    | `/books`                   | Retrieves a list of all books      | All users |
| GET    | `/books/{bookId}`          | Retrieves details of a specific book | All users |
| POST   | `/books`                   | Adds a new book to the inventory   | Admin     |
| PUT    | `/books/{bookId}`          | Updates a specific book            | Admin     |
| DELETE | `/books/{bookId}`          | Deletes a specific book            | Admin     |
| GET    | `/books/search`            | Searches books by criteria         | All users |
| POST   | `/users`                   | Registers a new user               | All users |
| POST   | `/users/login`             | User login                         | All users |
| POST   | `/orders`                  | Places a book order                | All users |
| GET    | `/orders/{orderId}`        | Retrieves a specific order         | All users |
| GET    | `/users/{userId}/orders`   | Retrieves all orders of a user     | User      |

