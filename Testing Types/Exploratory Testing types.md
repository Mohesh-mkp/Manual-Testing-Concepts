
---

## ✅ **Types of Exploratory Testing**

Exploratory Testing can be classified based on **structure**, **timeboxing**, and **tester intent**. Below are the most common types:

---

### 🔹 1. **Freestyle Exploratory Testing**

**📝 Description**:

* No specific plan, no charters
* The tester explores the application with full freedom

**📘 Example**:
You log into a new ride-sharing app and randomly try to:

* Book a ride without location
* Add fake payment details
* Cancel a trip halfway
  You're testing without any boundaries or predefined scope.

---

### 🔹 2. **Scenario-based Exploratory Testing**

**📝 Description**:

* Based on real-world **user scenarios or workflows**
* Tester explores how the system behaves during end-to-end activities

**📘 Example**:
In a banking app:

* Create a new account
* Deposit money
* Transfer funds
* Logout
  You explore these actions like a real user, testing for both **functional and usability** bugs.

---

### 🔹 3. **Session-based Exploratory Testing (SBT)**

**📝 Description**:

* Testing is **time-boxed** (e.g., 60–90 mins)
* A **charter or goal** is defined beforehand
* Tester documents what was tested, what issues were found, and what was learned

**📘 Example**:
Charter: Test the **cart and checkout** functionality of an e-commerce app in 90 minutes
You document:

* What flows you tested
* What bugs you found
* What areas need deeper testing next session

🛠 This type is useful for structured team work with **traceability**.

---

### 🔹 4. **Strategy-based Exploratory Testing**

**📝 Description**:

* You follow a particular **testing strategy**, like boundary value analysis or error guessing, but not formal test cases

**📘 Example**:
You test a **login form** using:

* Very long usernames
* SQL injection-like inputs
* Leaving the fields empty
  You're using a specific **heuristic** or **test technique** while still exploring freely.

---

## 🧩 Summary Table:

| Type                           | Description                                     | Example                               |
| ------------------------------ | ----------------------------------------------- | ------------------------------------- |
| Freestyle                      | No rules, open testing                          | Random usage of all app features      |
| Scenario-based                 | Based on real user flows                        | Test full banking workflow            |
| Session-based (SBTM)           | Time-boxed with documented goals                | 90-min focused test with reports      |
| Strategy-based (Technique-led) | Guided by a specific test strategy or technique | Input validation using error guessing |

---
