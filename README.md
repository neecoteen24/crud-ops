# 📘 Experiment 10: CRUD Operations using Node.js & Express.js

## 🎯 Objective

The objective of this experiment is to understand and implement CRUD (Create, Read, Update, Delete) operations using Node.js and Express.js with a MongoDB database.

---

## 💻 Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* Postman

---

## 📁 Project Structure

```
experiment10/
├── server.js
├── models/
│   └── Student.js
├── routes/
│   └── studentRoutes.js
├── package.json
```

---

## ⚙️ Installation & Setup

1. Initialize project:

```
npm init -y
```

2. Install dependencies:

```
npm install express mongoose cors nodemon
```

3. Start the server:

```
npx nodemon server.js
```

Server runs on:

```
http://localhost:5000
```

---

## 🧩 Features Implemented

### 1. Create Record

* Add new student data to database
* Fields: name, email, course

### 2. Read Records

* Fetch all student records
* Fetch single record using ID

### 3. Update Record

* Modify existing student data using ID

### 4. Delete Record

* Remove student record using ID

---

## 🔗 API Endpoints

| Method | Endpoint          | Description        |
| ------ | ----------------- | ------------------ |
| POST   | /api/students     | Create new student |
| GET    | /api/students     | Get all students   |
| GET    | /api/students/:id | Get single student |
| PUT    | /api/students/:id | Update student     |
| DELETE | /api/students/:id | Delete student     |

---

## 🧪 API Testing

APIs were tested using Postman.

### Sample Request (POST)

```json
{
  "name": "Rahul",
  "email": "rahul@gmail.com",
  "course": "BCA"
}
```

---

## 📸 Output Screenshots

The following outputs were verified:

* MongoDB connection success
* Create record response
* Read all records output
* Update record response
* Delete record response
* MongoDB collection view

---

## 🧠 Conclusion

This experiment helped in understanding how backend systems work using Node.js and Express.js. CRUD operations were successfully implemented and tested using REST APIs with MongoDB as the database.

---

## 👨‍💻 Author

Name: *[Your Name]*
Course: *[Your Course]*
Subject: Full Stack Development

---
