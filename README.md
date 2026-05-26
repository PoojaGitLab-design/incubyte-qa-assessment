[README.md](https://github.com/user-attachments/files/28259786/README.md)
# Gmail Compose – QA Test Cases
### Incubyte Software Craftsperson Assessment

---

## 📋 Feature Under Test

**Feature:** Gmail Compose Function  
**Action:** Send an email using the Gmail Compose window  
**Test Subject:** `Incubyte`  
**Test Body:** `QA test for Incubyte`  
**Application:** Gmail (https://mail.google.com)

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Gmail_Compose_Test_Cases_Incubyte.xlsx` | Complete test case document (Traditional + BDD) |
| `README.md` | This file |

---

## 🧪 Test Case Coverage

### Sheet 1 – Traditional Test Cases
Standard test cases written in a structured format with preconditions, steps, test data, and expected results.

| Category | Count |
|----------|-------|
| Positive Test Cases | 12 |
| Negative Test Cases | 12 |
| **Total** | **24** |

### Sheet 2 – BDD Test Cases
Behaviour-Driven Development style scenarios written in **Gherkin format** (Given / When / Then / And / But).

| Category | Count |
|----------|-------|
| Positive Scenarios | 9 |
| Negative Scenarios | 8 |
| **Total** | **17** |

---

## ✅ Areas Covered

- Opening the Compose window
- Entering recipient (To, CC, BCC)
- Entering Subject (`Incubyte`) and Body (`QA test for Incubyte`)
- Sending the email successfully
- Verifying email in Sent folder
- Saving and discarding drafts
- File attachments (valid and oversized)
- Minimize/restore compose window
- Validation errors (missing To, invalid email, missing subject)
- Network failure handling
- Security (XSS injection in Subject field)
- Edge cases (duplicate recipients, empty body, very long text, send to self)

---

## 📊 Test Case Format

### Traditional Style
Each test case includes:
- **Testcase_ID** – Unique identifier (e.g. TC-001)
- **Title** – Short description of the scenario
- **Feature** – Functional area being tested
- **Description** – What is being verified
- **Steps** – Step-by-step actions
- **Test Data** – Input parameters used
- **Expected Results** – What should happen
- **Actual Results** – To be filled during execution
- **TestCase_Status(Pass / Fail / Skipped)** – Execution outcome
- **Priority** – Critical / High / Medium / Low

### BDD Style (Gherkin)
Each scenario follows the format:
```gherkin
Given <precondition>
When  <action performed>
Then  <expected outcome>
And / But <additional assertion>
```

---

## 🔴 Priority Legend

| Priority | Meaning |
|----------|---------|
| Critical | Core user journey; must pass before any release |
| High | Key functionality; should be fixed before release |
| Medium | Important but non-blocking |
| Low | Minor / edge case; fix in future sprint |

---

## 👤 Submitted By: Pooja Malviya

**Assignment:** Incubyte Software Craftsperson – Manual QA Assessment  
**Date:** 2026-05-26
