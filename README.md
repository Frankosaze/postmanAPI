[![API Test Suite](https://github.com/Frankosaze/postmanAPI/actions/workflows/api-tests.yml/badge.svg)](https://github.com/Frankosaze/postmanAPI/actions/workflows/api-tests.yml)

# API Testing Portfolio – Postman Collection

This project contains an API testing suite executed in **Postman** and automated via **GitHub Actions + Newman**. The test suite validates Create, Read, Update, and Delete (CRUD) operations across multiple REST endpoints, ensuring correct response codes, data integrity, and payload structure consistency.

The CI pipeline runs automatically on every commit and displays real-time test results with the status badge above.

The goal of this work is to demonstrate:
- Ability to design and organize test flows
- Use of assertions to validate API responses
- Consistent testing approach across multiple endpoint types

---

## 📁 What This Test Suite Covers

| Test Area | Description |
|----------|-------------|
| **GET Requests** | Validate successful response codes and correct JSON fields |
| **POST Requests** | Confirm new data is created and returned with the correct structure |
| **PUT / PATCH Requests** | Verify updates are applied correctly and reflected in subsequent responses |

---

## 🛠️ Tools Used
- **Postman** for request execution & test management
- **JavaScript Assertions** inside Postman Tests tab
- **Environment Variables** for reusable values

---

## 👨‍💻 Author

**Frank Osaze**  
Software QA / Test Engineer  
GitHub: https://github.com/Frankosaze
Email: frankosazei@gmail.com
