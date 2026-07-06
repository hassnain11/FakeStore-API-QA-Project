# 🛒 Fake Store API QA Project

## 📌 Project Overview

This project demonstrates manual API testing of the Fake Store API using Postman and Jira. The primary objective was to validate API functionality, verify CRUD operations, perform positive and negative testing, identify defects, and document all testing activities following industry-standard QA practices.

---

# 🎯 Project Objectives

- Verify REST API functionality
- Validate CRUD operations
- Perform Positive Testing
- Perform Negative Testing
- Verify HTTP Status Codes
- Identify API validation issues
- Report defects in Jira
- Document testing artifacts

---

# 🛠️ Tools Used

- Postman
- Jira
- Microsoft Excel
- Microsoft Word
- GitHub

---

# 🌐 API Under Test

Base URL

https://fakestoreapi.com/

---

# 📋 Test Scope

The following API operations were tested:

## GET

- Get All Products
- Get Product by ID
- Get Invalid Product ID

## POST

- Create Product
- Create Product with Negative Price

## PUT

- Update Product
- Update Product with Negative Price
- Update Product with Empty Title

## DELETE

- Delete Product
- Delete Non-Existing Product

---

# ✅ Testing Types Performed

- Functional Testing
- API Testing
- Positive Testing
- Negative Testing
- Validation Testing
- CRUD Testing
- Regression Testing (Basic)

---

# 📊 Test Execution Summary

| Metric | Result |
|---------|--------|
| Total Test Cases | 10 |
| Executed | 10 |
| Passed | 5 |
| Failed | 5 |
| Pass Rate | 50% |
| Fail Rate | 50% |

---

# 🐞 Bugs Identified

| Bug ID | Description | Status |
|---------|-------------|--------|
| BUG-001 | GET API returns success for non-existent product ID | Reported |
| BUG-002 | POST API accepts negative price | Reported |
| BUG-003 | PUT API accepts negative price | Reported |
| BUG-004 | PUT API accepts empty product title | Reported |
| BUG-005 | DELETE API returns success for non-existent product ID | Reported |

---

# 📂 Repository Structure

```
FakeStore-API-QA-Project
│
├── README.md
├── 1_API_Test_Plan.docx
├── 2_API_Test_Cases.xlsx
├── 3_API_Test_Execution_Report.xlsx
├── Postman_Collection.json
│
├── Bug_Screenshots
│
└── Jira_Screenshots
```

---

# 📁 Project Deliverables

- API Test Plan
- API Test Cases
- API Test Execution Report
- Postman Collection
- Jira Bug Reports
- Bug Screenshots
- Jira Screenshots

---

# ▶️ How to Run the Project

1. Download the repository.
2. Open Postman.
3. Import **Postman_Collection.json**.
4. Execute the requests.
5. Verify the responses.
6. Review the documented Jira bugs.
7. Compare the actual results with the expected results in the test cases.

---

# 📸 Screenshots Included

### Jira

- Jira Board
- Bug 001
- Bug 002
- Bug 003
- Bug 004
- Bug 005

### Postman

- GET Invalid Product ID
- POST Negative Price
- PUT Negative Price
- PUT Empty Title
- DELETE Invalid Product ID

---

# 📚 Skills Demonstrated

- Manual API Testing
- REST API Testing
- CRUD Operations
- Postman
- Jira
- Bug Reporting
- Test Planning
- Test Case Design
- Test Execution
- Defect Tracking
- GitHub Documentation

---

# 🚀 Future Improvements

- API Automation using Postman Tests
- Newman CLI Integration
- CI/CD Pipeline Integration
- Response Schema Validation
- Performance Testing
- Authentication Testing

---

# 👨‍💻 Author

**Muhammad Hassnain Raza**

Software Engineering Graduate

Aspiring Software Quality Assurance (SQA) Engineer

GitHub: https://github.com/hassnain11

---

# ⭐ If you found this repository useful, please consider giving it a Star.
