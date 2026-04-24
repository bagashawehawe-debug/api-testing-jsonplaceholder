# User API Testing – JSONPlaceholder

## 📌 Description
This project demonstrates basic API testing using Postman, covering CRUD operations (Create, Read, Update, Delete) on the JSONPlaceholder public API.

## 🛠 Tools
- Postman

## 🔍 Test Coverage
- Validate HTTP status codes
- Validate response structure
- Validate response data
- Basic negative testing

## 📡 Endpoints Tested
- GET /users/1 → Get user detail
- POST /users → Create new user
- PUT /users/1 → Update user
- DELETE /users/1 → Delete user

## 🧪 Test Scenarios
- Verify GET /users/1 returns valid user data
- Verify POST /users creates new user with status 201
- Verify PUT /users/1 updates user data correctly
- Verify DELETE /users/1 returns success status

## ## 📊 Validation Performed
- Status code validation (200, 201, 204)
- Response structure validation
- Data existence validation (id, name)
- Basic negative testing

## ✅ Test Results
All test cases executed successfully and passed.

## 📁 Project Files
- Postman Collection (.json)

## 💡 Notes
This project focuses on validating API behavior using basic test scripts in Postman. 
The goal is to simulate real QA testing scenarios such as validating response data, 
status codes, and handling edge cases.

## 👤 Author
Muhammad Bagas Hardjawinangun
