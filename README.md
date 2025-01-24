# BookstoreAPI
A learning project for FastAPI

| Endpoint                | Method | Description                                              |
|-------------------------|--------|----------------------------------------------------------|
| `/books`                | GET    | Retrieves a list of all books available in the bookstore.|
| `/books/{bookId}`       | GET    | Retrieves detailed information about a specific book.    |
| `/books`                | POST   | Adds a new book to the bookstore inventory.              |
| `/books/{bookId}`       | PUT    | Updates information for an existing book.                |
| `/books/{bookId}`       | DELETE | Removes a book from the bookstore inventory.             |
| `/books/search`         | GET    | Searches the inventory for books by title, author, or ISBN.|
| `/users`                | POST   | Registers a new user in the system.                      |
| `/users/login`          | POST   | Authenticates a user and returns a token.                |
| `/orders`               | POST   | Places a new order for books.                            |
| `/orders/{orderId}`     | GET    | Retrieves details of a specific order.                   |
| `/users/{userId}/orders`| GET    | Retrieves a list of orders placed by a specific user.    |
