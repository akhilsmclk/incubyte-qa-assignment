---

## 📊 What's Inside the Excel

The workbook has **2 sheets**

---

### Sheet 1 — Traditional Test Cases

Step-by-step test cases in standard QA format.

| Column | Description |
|---|---|
| TC ID | Unique identifier (TC_01 to TC_19) |
| Test Scenario | What is being tested |
| Test Type | Positive / Negative |
| Priority | P1 (Critical) / P2 (High) / P3 (Medium) |
| Preconditions | Setup required before execution |
| Test Steps | Numbered step-by-step actions |
| Test Data | Exact input values used |
| Expected Result | What the system should do |

**Total: 19 test cases — 10 Positive + 9 Negative**

| Type | TCs |
|---|---|
| Positive | TC_01 to TC_10 |
| Negative | TC_11 to TC_19 |

---

### Sheet 2 — BDD Test Cases (Gherkin Style)

Behaviour-driven scenarios written in **Given / When / Then** format.

| Column | Description |
|---|---|
| TC ID | Unique identifier (BDD_01 to BDD_15) |
| Scenario Title | What is being tested |
| Type | Positive / Negative |
| Priority | P1 / P2 / P3 |
| Given | Pre-state / context |
| When | User action |
| Then | Expected outcome |

**Total: 15 BDD scenarios — 9 Positive + 6 Negative**

---

## 🔍 Test Coverage

| Area | Covered |
|---|---|
| Core send flow | ✅ Valid recipient, correct subject & body |
| Email delivery verification | ✅ Recipient receives correct subject & body |
| Recipient validation | ✅ Empty, invalid format, whitespace-only |
| Subject / Body | ✅ Empty subject warning, empty body behaviour |
| CC / BCC | ✅ CC send, BCC visibility to To recipient |
| Draft | ✅ Auto-save, send from draft |
| Undo Send | ✅ Recall within cancellation window |
| Attachments | ✅ Valid file, >25MB limit, blocked .exe |
| Data validation | ✅ Wrong subject, wrong body content |
| Network failure | ✅ Send during internet disconnection |

---

## ⚡ Priority Scale

| Priority | Meaning |
|---|---|
| P1 | Critical — blocks core functionality |
| P2 | High — major feature impacted |
| P3 | Medium — minor or edge case |

---

## 🛠 Test Environment

- **Application:** Gmail Web App
- **Browser:** Chrome / Firefox / Edge
- **Type:** Manual Testing
- **Techniques:** Equivalence Partitioning, Boundary Value Analysis, Error Guessing.

---

## 👤 Submitted By

- **Akhil S M**
- Senior Test Engineer
- Linkedin - https://www.linkedin.com/in/akhilsm27/
