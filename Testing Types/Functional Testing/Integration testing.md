### ✅ What is Integration Testing?

**Integration Testing** is a type of software testing where **individual modules or components are combined and tested as a group** to verify that they work together correctly.

It focuses on **data flow and interaction** between integrated units, modules, or systems.

---

## 🔄 Why Integration Testing is Important:

* Modules may work fine **individually**, but **fail when combined**.
* Detects issues like:

  * Incorrect data passing between modules
  * Interface mismatches
  * API call failures
  * Incorrect function calls between units

---

## 🧪 When is Integration Testing Done?

* After **unit testing** is completed
* Before or during **system testing**
* In **incremental development**, after integrating new components

---

## 🔷 Example:

Let’s say you are testing an online food ordering app. It has 3 modules:

1. **Login Module**
2. **Menu Display Module**
3. **Cart and Checkout Module**

Individually:

* Login works ✅
* Menu loads fine ✅
* Cart accepts items ✅

But in integration testing, you test:

* **Login → Menu → Add to Cart → Checkout**
* Ensure data (like selected items, user ID, payment details) **flows correctly between these modules**

If login passes wrong user ID to the cart → integration test fails.

---

## 🔑 Key Points:

| Aspect   | Description                                    |
| -------- | ---------------------------------------------- |
| Focus    | Interfaces and data flow between modules       |
| Type     | Functional testing                             |
| Approach | Top-down, bottom-up, big bang, or hybrid       |
| Tools    | JUnit, TestNG, Postman (for API), SoapUI, etc. |

---

## 🧩 Types of Integration Testing:

| Type                | Description                                                |
| ------------------- | ---------------------------------------------------------- |
| **Big Bang**        | All modules integrated and tested together at once (risky) |
| **Top-Down**        | Start testing from top-level modules and move downward     |
| **Bottom-Up**       | Start testing from lower-level modules and go upward       |
| **Sandwich/Hybrid** | Mix of top-down and bottom-up approaches                   |

---

## 🎯 Real-world Analogy:

Imagine testing a **car**:

* You tested the **engine**, **brakes**, and **steering** separately.
* Now you install them all in the car and test how they **work together**.

That’s **Integration Testing** — ensuring that individually working parts function properly as a **combined system**.

---
