# Node Express Books API

A simple **RESTful API** built with **Node.js, Express, and SQLite3** for managing books data.
This project demonstrates CRUD operations, database integration, and Docker deployment for easy setup.

---

## 🚀 Features

* Create, Read, Update, and Delete (CRUD) operations on books
* SQLite3 database integration
* RESTful API design principles
* Docker support for containerized deployment
* API documentation for easy usage

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express
* **Database:** SQLite3 (with Knex.js)
* **Deployment:** Docker

---

## 📂 Project Structure

```
├── db/                # Database configuration and queries
├── server.js          # Entry point of the API
├── package.json       # Dependencies and scripts
├── books-data.csv     # Sample books dataset
├── booksdb.sqlite3    # SQLite database file
├── Dockerfile         # Docker setup
└── api-guide.txt      # API usage guide
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/samiul501/Books-api-express-with-JMETER.git
cd Books-api-express-with-JMETER/node-express-api-books-master
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Locally

```bash
npm start
```

The server will start on **[http://localhost:3000](http://localhost:3000)**

---

## 🐳 Run with Docker

```bash
docker build -t books-api .
docker run -p 3000:3000 books-api
```

---

## 📖 API Endpoints

| Method | Endpoint     | Description             |
| ------ | ------------ | ----------------------- |
| GET    | `/books`     | Get all books           |
| GET    | `/books/:id` | Get a single book by ID |
| POST   | `/books`     | Add a new book          |
| PUT    | `/books/:id` | Update a book by ID     |
| DELETE | `/books/:id` | Delete a book by ID     |

For detailed usage, see **`api-guide.txt`**.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

Developed by **Samiul Islam**
