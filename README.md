# API Testing Portfolio – Postman Collection

This project shows practical API testing using **Postman**, focused on verifying data retrieval, creation, update, and deletion of resources through RESTful endpoints.

The goal of this work is to demonstrate:
- Ability to design and organize test flows
- Use of assertions to validate API responses
- Consistent testing approach across multiple endpoint types

---

## What This Test Suite Covers

| Test Area | Description |
|----------|-------------|
| **GET Requests** | Validate successful response codes and correct JSON fields |
| **POST Requests** | Confirm new data is created and returned with the correct structure |
| **PUT / PATCH Requests** | Verify updates are applied correctly and reflected in subsequent responses |
| **DELETE Requests** | Ensure resources are removed successfully and return expected messages |

---

## Tools Used
- **Postman** for request execution & test management
- **JavaScript Assertions** inside Postman Tests tab
- **Environment Variables** for reusable values

---

## Example Assertion

```javascript
pm.test("Response status is 200", () => {
  pm.response.to.have.status(200);
});

pm.test("Response returns valid data object", () => {
  const json = pm.response.json();
  pm.expect(json).to.be.an("object");
});
