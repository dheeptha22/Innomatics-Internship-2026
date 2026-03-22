# 🚀 FastAPI Online Course Platform

## 📌 Project Overview

This project is a backend application built using **FastAPI** that simulates an **Online Course Platform**.

It allows users to manage courses by performing operations like creating, viewing, updating, and deleting course data. The project demonstrates real-world backend development concepts such as API design, database integration, and data validation.

---

## 🎯 Features

✨ Create Course (POST API)
✨ View All Courses (GET API)
✨ Get Course by ID
✨ Update Course
✨ Delete Course
✨ Search Courses 🔍
✨ Pagination 📄
✨ Data Validation using Pydantic ✔️

---

## 🛠️ Tech Stack

* ⚡ FastAPI
* 🐍 Python
* 🗄️ SQLAlchemy
* 💾 SQLite
* 🚀 Uvicorn

---

## 📂 Project Structure

```
PROJECT_FASTAPI/
   ├── fastapi-course-platform/
   │      ├── main.py
   │      ├── crud.py
   │      ├── models.py
   │      ├── schemas.py
   │      ├── database.py
   │      └── requirements.txt
   │
   ├── screenshots/
   │      ├── create.png
   │      ├── get.png
   │      ├── search.png
   │      ├── update.png
   │
   └── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/dheeptha22/Innomatics-Internship-2026.git
```

### 2️⃣ Navigate to Project Folder

```
cd PROJECT_FASTAPI/fastapi-course-platform
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Server

```
python -m uvicorn main:app --reload
```

### 5️⃣ Open Swagger UI

```
http://127.0.0.1:8000/docs
```

---

## 🧪 API Examples

### ➤ Create Course

POST `/courses/`

```
{
  "title": "Python Basics",
  "instructor": "John",
  "price": 999
}
```

---

### ➤ Get All Courses

GET `/courses/`

With Pagination:

```
/courses?skip=0&limit=2
```

With Search:

```
/courses?search=Python
```

---

### ➤ Get Course by ID

```
/courses/1
```

---

### ➤ Update Course

```
/courses/1
```

---

### ➤ Delete Course

```
/courses/1
```

---

## 📸 Screenshots

Add your Swagger screenshots here:

```
screenshots/
```

Example:

```
![Create API](screenshots/create.png)
```

---

## 💡 Key Learnings

✔ Built REST APIs using FastAPI
✔ Implemented CRUD operations
✔ Used SQLAlchemy for database handling
✔ Applied Pydantic for validation
✔ Implemented search and pagination
✔ Structured backend like a real-world project

---

## 🚀 Future Improvements

🔐 Authentication (JWT)
👤 User roles (Admin/User)
📦 Bulk course upload
💳 Payment integration
🌐 Cloud deployment

---

## 👩‍💻 Author

**Dheeptha**

---

## 📢 Acknowledgement

This project was developed as part of the **Innomatics Research Labs Internship Program**.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
