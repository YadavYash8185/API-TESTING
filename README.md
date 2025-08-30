# API-TESTING 🚀

A comprehensive API testing project using **ReqRes API** for demonstrating various HTTP methods and testing scenarios.

## 📋 Project Overview

This project contains automated API tests for the ReqRes.in API service, covering all CRUD operations (Create, Read, Update, Delete) with comprehensive test documentation and validation.

## 🛠️ Technologies Used

- **API Testing Tool:** Postman
- **Test API:** ReqRes.in (https://reqres.in/)
- **Documentation:** Excel for test case management
- **HTTP Methods:** GET, POST, PUT, DELETE
- **Data Format:** JSON

## 📁 Project Structure

API-TESTING/
├── API-TestCases.xlsx # Detailed test cases with expected results
├── ReqRes-API-Testing-by-Yash.postman_collection.json # Postman collection
└── README.md # Project documentation

## 🧪 Test Cases Covered

| Test ID | Method | Endpoint | Purpose | Status Code |
|---------|--------|----------|---------|-------------|
| 1 | GET | `/api/users?page=2` | Retrieve user list (page 2) | 200 |
| 2 | POST | `/api/users` | Create new user | 201 |
| 3 | PUT | `/api/users/514` | Update existing user | 200 |
| 4 | DELETE | `/api/users/514` | Delete user | 204 |

## 🚀 Getting Started

### Prerequisites
- Postman installed on your machine
- Internet connection for API calls


## 🔧 How to Run Tests

### Using Postman:
1. Open the imported collection
2. Select any request (Get Request, Post Request, etc.)
3. Click "Send" to execute
4. Verify response matches expected results from Excel file
