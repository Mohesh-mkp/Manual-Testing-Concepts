### ✅ What is Regression Testing?

**Regression Testing** is a type of software testing that ensures **new code changes do not break or affect the existing functionality** of the application.

It’s done **every time code is changed** – whether for bug fixes, enhancements, or new features.

---

## 🔁 Why is it called “Regression”?

The word **“regression”** means “going backward”. So, regression testing ensures that the **application hasn't regressed (broken) after changes** were made.

---

## 📌 When is Regression Testing Done?

* After **bug fixes**
* After **code enhancements or changes**
* Before major **release cycles**
* During **continuous integration** builds

---

## 🔷 Example:

Let’s say you fix a bug in the **payment screen**.

* A regression test will ensure:

  * Login still works
  * Product search works
  * Cart and Checkout flows are intact
  * The **entire payment flow** works as expected

Even though you didn’t touch the login or cart code, those areas must be tested to make sure nothing got unintentionally affected.

---

## 🧪 How Regression Testing is Performed:

* By running **existing test cases** (manual or automated)
* Testers may use a **regression test suite** (pre-defined test scripts for critical flows)

---

## 🔑 Key Points:

| Aspect         | Details                                     |
| -------------- | ------------------------------------------- |
| Purpose        | To confirm that existing features work fine |
| Triggered by   | Code changes, bug fixes, feature additions  |
| Scope          | Broad (all related and impacted modules)    |
| Test Case Type | Reusable, often automated                   |
| Example Tool   | Selenium, Robot Framework, Cypress, etc.    |

---

## 🎯 Real-life Analogy:

Imagine updating your smartphone’s camera app. You need to check that:

* Camera works ✅
* Gallery still opens ✅
* Other apps like WhatsApp or Zoom still function ✅

That’s regression testing — confirming the update **didn’t break the rest of the system**.

---
