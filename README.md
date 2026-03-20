# qa-login-project
QA project focused on login testing, including test cases, bug reports, API tests and exploratory testing.

# 🧪 QA Portfolio - Login Testing Project

## 📌 Objective
This project aims to demonstrate practical skills in Software Quality Assurance (QA), focusing on testing a login functionality through manual testing, API testing, and exploratory testing.

---

## 🛠️ Tools Used
- Postman (API testing)
- GitHub (version control and documentation)
- Markdown (test documentation)

---

## 🔍 Test Scope

The following test scenarios were covered:

- Positive tests (valid login)
- Negative tests (invalid credentials)
- Validation of required fields
- API response validation (status codes and messages)

---

## 🧠 Test Strategy

The testing approach prioritized critical authentication scenarios, focusing on:

- Input validation
- Error handling
- Response consistency

Authentication was considered a high-risk area due to its impact on system security.

---

## 📁 Project Structure

- `test-cases` → Manual test cases
- `bug-reports` → Identified issues and inconsistencies
- `api-tests` → API test scenarios and results
- `exploratory-tests` → Exploratory testing notes

---

## 🐞 Key Findings

- API returned inconsistent status codes (e.g., 201 instead of 200 for login)
- Some APIs blocked requests (Cloudflare protection)
- Inconsistent validation behavior across different APIs

---

## ⚠️ Risks Identified

- Improper validation of credentials
- Inconsistent API responses
- Potential misinterpretation of status codes by clients

---

## 📊 Conclusion

The tests revealed inconsistencies in API behavior and highlighted the importance of proper validation and standard response handling in authentication systems.

---

## 🚀 Author
Daniel Pavan
