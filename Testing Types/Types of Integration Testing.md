
---

## ✅ Types of Integration Testing

There are **four main types** of Integration Testing:

---

### 1. **Big Bang Integration Testing**

**➤ All modules are integrated together and tested as a whole.**

* No incremental integration — everything is plugged in at once.
* Simple to implement, but hard to debug when failures occur.

🔹 **Use When**: The application is small, or you receive the entire system at once.

🧪 **Example**: In a banking app, you combine login, balance check, transfer, and logout modules and test them all together — without checking them in steps.

⚠️ **Drawback**: If there’s an error, it’s tough to isolate the faulty module.

---

### 2. **Top-Down Integration Testing**

**➤ Start from the top (main module) and integrate downward step by step.**

* Test high-level modules first, then integrate submodules.
* Use **stubs** for modules that are not yet developed.

🔹 **Use When**: The flow of control is from top to bottom (e.g., menu → sub-features).

🧪 **Example**: Test the main "Dashboard" module first, then add and test "User Profile", "Settings", and "Notifications" modules underneath it.

---

### 3. **Bottom-Up Integration Testing**

**➤ Start from the bottom (low-level modules) and integrate upward.**

* Lower-level modules are tested first.
* Use **drivers** to simulate the upper modules that call them.

🔹 **Use When**: Low-level modules are ready first and control/data flows upward.

🧪 **Example**: Test database and service layers first, then integrate them with the UI later.

---

### 4. **Sandwich (Hybrid) Integration Testing**

**➤ Combination of Top-Down and Bottom-Up approaches.**

* Test top-level and bottom-level modules simultaneously.
* Middle modules are tested later.

🔹 **Use When**: You want to speed up testing and both top and bottom modules are available.

🧪 **Example**: While testing an e-commerce app, test:

* Top: UI + Login → downward
* Bottom: Database + API → upward
  Then connect both to test middle layers like payment gateway.

---

## 🧩 Summary Table:

| Type              | Direction       | Uses Stubs/Drivers | Suitable For                       |
| ----------------- | --------------- | ------------------ | ---------------------------------- |
| Big Bang          | All at once     | No                 | Small systems or one-shot delivery |
| Top-Down          | Top → Down      | Stubs              | When top modules are ready early   |
| Bottom-Up         | Bottom → Up     | Drivers            | When lower modules are ready first |
| Sandwich (Hybrid) | Both directions | Both               | Complex, large systems             |

---
