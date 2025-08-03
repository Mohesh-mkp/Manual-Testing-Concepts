
---
## 🔍 **Types of Ad-hoc Testing**
---

## 🧪 1. **Donkey Testing**

### ✅ **Definition**:

An **informal, brute-force style of testing** with **no understanding of the logic or flow** of the application. It is done randomly and carelessly.

### 🎯 **Purpose**: To uncover bugs accidentally through haphazard interaction.

### 💡 **Example**:

A tester enters numbers in the name field, clicks buttons randomly, or force-submits incomplete forms without understanding what they’re supposed to do.

---

## 🐵 2. **Monkey Testing**

### ✅ **Definition**:

Testing where **random inputs and actions** are performed to **see if the system crashes**. No predefined scenarios or test cases are used.

### 🎯 **Purpose**: To find system crashes or unexpected errors through **randomness**.

### 💡 **Example**:

A tester inputs special characters or extremely long strings into all input fields and navigates rapidly without following any user flow.

---

## 🦍 3. **Gorilla Testing**

### ✅ **Definition**:

Repetitive and **focused testing of a single module or functionality**. The goal is to **stress-test** one component thoroughly.

### 🎯 **Purpose**: To ensure a particular module can handle heavy usage without breaking.

### 💡 **Example**:

Uploading and deleting the same file repeatedly in a document upload feature to verify stability.

---

## 👥 4. **Buddy Testing**

### ✅ **Definition**:

A **tester and a developer** work together as buddies to test an application jointly. They share knowledge and find bugs early.

### 🎯 **Purpose**: To combine dev + test perspectives and catch defects early in development.

### 💡 **Example**:

A developer builds a new checkout page, and the tester sits with them to test form validation, error messages, and transitions before formal testing begins.

---

## 👨‍💻👩‍💻 5. **Pair Testing**

### ✅ **Definition**:

Two **testers** work together on the same feature – one operates the app, the other observes and provides ideas or notes.

### 🎯 **Purpose**: To combine two testing minds for **broader test coverage**.

### 💡 **Example**:

One tester inputs test data into a form, while the other checks the logs and backend behavior for data flow correctness.

---

## 📊 Summary Table:

| Type            | Who is Involved             | Approach         | Focus Area        | Example                                             |
| --------------- | --------------------------- | ---------------- | ----------------- | --------------------------------------------------- |
| Donkey Testing  | Tester alone                | Random, careless | General usage     | Pressing random buttons & submitting empty forms    |
| Monkey Testing  | Tester (no app knowledge)   | Random input     | Entire system     | Inputting special characters everywhere             |
| Gorilla Testing | Tester (with app knowledge) | Repetitive       | One module        | Repeated file uploads in one feature                |
| Buddy Testing   | Developer + Tester          | Collaborative    | Feature under dev | Testing login form during development               |
| Pair Testing    | Two Testers                 | Collaborative    | Any area          | One tests UI, another checks backend simultaneously |

---

| Type                | Description                                                                                      | Example                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------- |
| **Monkey Testing**  | Random inputs and actions, without logic                                                         | Entering random characters into every field                                     |
| **Gorilla Testing** | Focusing heavily on one feature/module with repeated actions                                     | Uploading the same file multiple times to test file upload                      |
| **Buddy Testing**   | Two testers (often a developer + tester) test together to share knowledge and explore the system | Tester and developer test the login functionality together                      |
| **Pair Testing**    | Two testers work collaboratively on the same system                                              | One tester drives, the other observes and suggests                              |
| **Donkey Testing**  | Informal term used for careless or brute-force testing with minimal planning                     | Randomly clicking buttons and navigating screens without understanding the flow |

---

## 🧠 **Quick Comparison Table**

| Type            | Planning | Collaboration  | Scope            | Focus Area          |
| --------------- | -------- | -------------- | ---------------- | ------------------- |
| Monkey Testing  | None     | No             | Entire app       | Random behavior     |
| Gorilla Testing | None     | No             | One module       | Repetition strength |
| Buddy Testing   | Low      | Yes (Dev + QA) | Multiple modules | Knowledge sharing   |
| Pair Testing    | Low      | Yes (QA + QA)  | Specific areas   | Exploratory & fast  |
| Donkey Testing  | None     | No             | Random           | Careless/random use |

---

## 📌 Summary

* **Ad-hoc Testing** is useful when formal testing is done, or time is short.
* It helps catch **unexpected bugs** and edge cases.
* Works best when testers have a good understanding of the app.

---
