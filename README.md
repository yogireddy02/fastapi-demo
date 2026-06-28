# 📦 FastAPI Demo Products with UI

A simple FastAPI application for managing products using CRUD operations.

This project demonstrates the integration of **FastAPI**, **SQLAlchemy**, **Pydantic**, and **PostgreSQL** to build a RESTful API with automatic documentation.

---

## 🚀 Features

* FastAPI REST API
* SQLAlchemy ORM integration
* PostgreSQL database support
* Pydantic data validation
* CRUD operations for products
* Interactive API documentation
* Clean project structure

---

## 🛠️ Tech Stack

* **FastAPI** – Modern Python web framework
* **SQLAlchemy** – ORM for database operations
* **PostgreSQL** – Relational database
* **Pydantic** – Data validation and serialization
* **Uvicorn** – ASGI server

---

## 📂 Project Structure

```text
fastapi-demo-products-with-ui/
│
├── main.py                # FastAPI application entry point
├── database.py            # Database connection setup
├── database_models.py     # SQLAlchemy models
├── models.py              # Pydantic schemas
├── frontend/              # Frontend assets (optional)
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yogireddy02/fastapi-demo.git
cd fastapi-demo-products-with-ui
```

### 2️⃣ Create a Virtual Environment

**Windows**

```bash
python -m venv myenv
myenv\Scripts\activate
```

**Linux / macOS**

```bash
python -m venv myenv
source myenv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt` file:

```bash
pip freeze > requirements.txt
```

### 4️⃣ Start the Application

```bash
uvicorn main:app --reload
```

The server will start at:

```text
http://127.0.0.1:8000
```

---

## 📖 API Documentation

FastAPI automatically generates interactive API documentation.

### Swagger UI

```text
http://127.0.0.1:8000/docs
```

### ReDoc

```text
http://127.0.0.1:8000/redoc
```

---

## 📌 Available Endpoints

| Method | Endpoint        | Description                |
| ------ | --------------- | -------------------------- |
| GET    | `/`             | Welcome message            |
| GET    | `/products`     | Retrieve all products      |
| GET    | `/product/{id}` | Retrieve a product by ID   |
| POST   | `/product`      | Create a new product       |
| PUT    | `/product`      | Update an existing product |
| DELETE | `/product`      | Delete a product           |

---

## 🧩 Sample Product Payload

```json
{
  "id": 1,
  "name": "Phone",
  "description": "A smartphone",
  "price": 699.99,
  "quantity": 50
}
```

---

## 🤝 Contributing

Contributions are welcome.

If you would like to make major changes, please open an issue first to discuss your proposed changes.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Yogavardhan Reddy**

GitHub: https://github.com/yogireddy02

```
```
