# Junior Quality Engineering Technical Test

This repository contains the deliverables for the **Quality Engineering test**.  
It is divided into two main tasks:  

- **Task 1 – UI / Functional Testing (Pet Store website)**  
- **Task 2 – API / Integration Testing (Swagger Petstore API)**  

The goal of this assessment was to demonstrate test design, coverage strategy, and maintainable test automation.  

---

## Task 1 – Pet Store UI Testing  

### Deliverables  
- **petstore testcases 01.xlsx** – Detailed test cases (functional, negative, boundary, non-functional)  
- **coverage matrix.xlsx** – Mapping of test cases to testing levels & types  
- **acceptance tests.md** – End-to-end acceptance tests in *Given / When / Then* format  
- **conclusion.md** – Strategy summary, coverage explanation, and next steps  

### Testing Levels Covered  
- **Integration** – Login, cart operations, browsing  
- **System** – Registration, checkout, order history  
- **Acceptance** – Real-world workflows (purchase flow, login/logout, cart management)  
- **Unit (limited)** – More relevant in Task 2 API tests  

---

## Task 2 – Pet Store API / Integration Testing  

### Deliverables  
- **postman collection.json** – Postman collection with integration tests for `/pet` endpoint  
- **postman environment.json** – Configurable variables (base URL, pet IDs)  
- **conclusion.md** – Test structure explanation and maintainability considerations  

### Key API Test Coverage  
- Create a pet (POST)  
- Retrieve a pet (GET)  
- Update a pet (PUT)  
- Delete a pet (DELETE)  
- Negative tests (invalid IDs, missing fields)  

### Running the Tests (Postman)  
1. Import `postman_collection.json` into Postman  
2. Import `postman_environment.json` into Postman  
3. Select the environment and run the collection in the Postman Collection Runner  

---

## Summary  

This repo demonstrates a **balanced approach**:  
- **Task 1**: Clear, descriptive test cases and coverage analysis for the UI  
- **Task 2**: Automated, maintainable integration tests for the Pet Store API  
- Focused on **efficiency, clarity, and maintainability**
