
---

## ✅ **What is Unit Testing?**

**Unit Testing** is the **first level of testing** where **individual components (units)** of software (like functions, methods, or classes) are tested in **isolation** to ensure they work correctly.

---

## 🎯 **Purpose of Unit Testing:**

* Verify that **each small piece** of code performs as expected
* Help identify bugs early in the development phase
* Make future changes safer (regression-safe)

---

## 👨‍💻 **Who Performs It?**

* Typically **developers**, during the coding phase

---

## 📘 **Example:**

Suppose you have a function in an e-commerce app:

```python
def calculate_total(price, quantity):
    return price * quantity
```

A **unit test** would check:

```python
assert calculate_total(100, 2) == 200
assert calculate_total(50, 0) == 0
assert calculate_total(0, 10) == 0
```

Each test verifies that the **function behaves correctly** for different inputs.

---

## 🧪 **Unit Testing Tools:**

* Python → `unittest`, `pytest`
* Java → `JUnit`
* JavaScript → `Jest`, `Mocha`
* C# → `NUnit`

---

## 🧩 Summary Table:

| Feature          | Description                                  |
| ---------------- | -------------------------------------------- |
| **Scope**        | Smallest unit of code (e.g., function/class) |
| **Performed By** | Developers                                   |
| **Goal**         | Ensure individual components work correctly  |
| **Environment**  | Development                                  |
| **Automation**   | Mostly automated using unit test frameworks  |

---
