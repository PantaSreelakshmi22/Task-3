# 📚 Book Manager REST API

A simple REST API built with Node.js and Express to manage a list of books in memory (no database). This API supports full CRUD (Create, Read, Update, Delete) operations.

---

## 📌 Features

- Get all books ✅
- Add a new book ✅
- Update a book by ID ✅
- Delete a book by ID ✅

---

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **Postman** (for testing)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/book-api.git
cd book-api
2. Install Dependencies
bash
Copy
Edit
npm install express
3. Run the Server
bash
Copy
Edit
node server.js
Server will start at:

arduino
Copy
Edit
http://localhost:3000
📂 API Endpoints
➤ Get All Books
URL: GET /books

Response:

json
Copy
Edit
[
  {
    "id": 1,
    "title": "1984",
    "author": "George Orwell"
  }
]
➤ Add a New Book
URL: POST /books

Headers: Content-Type: application/json

Body:

json
Copy
Edit
{
  "id": 3,
  "title": "Reading Books",
  "author": "Panta Sree Lakshmi"
}
➤ Update a Book
URL: PUT /books/:id

Example: PUT /books/3

Body:

json
Copy
Edit
{
  "title": "Updated Title",
  "author": "Updated Author"
}
➤ Delete a Book
URL: DELETE /books/:id

Example: DELETE /books/3

🧪 Testing with Postman
Open Postman

Use the sample requests provided above

Make sure the server is running at http://localhost:3000

📄 License
This project is open-source and free to use for learning purposes.

👩‍💻 Author
Sreelakshmi
Created as part of a Node.js learning task.


