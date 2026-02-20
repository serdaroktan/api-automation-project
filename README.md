# API Automation Project

This project demonstrates API test automation using Postman and Newman.

## 🚀 Technologies Used

- Postman
- Newman (CLI)
- Node.js
- Git

---

## 📌 Test Scenarios

### 1️⃣ GET /posts/1
- Expected Status: 200 OK
- Response validation
- Response time validation

### 2️⃣ GET /posts/9999
- Expected Status: 404 Not Found
- Negative test scenario

### 3️⃣ POST /posts
- Expected Status: 201 Created
- ID validation
- Response structure validation

---

## 🛠 How to Run Tests

Install Newman:

```bash
npm install -g newman