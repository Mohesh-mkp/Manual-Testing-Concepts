
---

## ✅ **What is Severity?**

**Severity** defines **how serious** a bug is in terms of its **impact on the application’s functionality**.

* **Set by**: Tester
* **Focuses on**: Technical impact
* **Answers**: *“How badly does this bug break the system?”*

### 🔷 Example:

> If the **login page crashes** when you click “Submit”, that’s a **high severity** bug because it prevents users from accessing the system.

---

## ✅ **What is Priority?**

**Priority** defines **how urgently** the bug needs to be **fixed or resolved** based on **business needs or release schedules**.

* **Set by**: Product Owner / Project Manager / Dev Lead
* **Focuses on**: Business urgency
* **Answers**: *“How soon should we fix this?”*

### 🔷 Example:

> If there’s a **spelling mistake on the homepage**, the severity is **low**, but the **priority may be high** because it affects the company’s branding.

---

## 📝 **Simple Analogy**

> Imagine a **hospital**:
>
> * **Severity** = **How critical** is the patient's condition?
> * **Priority** = **How urgently** should the patient be treated?

---

## 🔁 **Summary Table**

| **Criteria** | **Severity**                     | **Priority**                           |
| ------------ | -------------------------------- | -------------------------------------- |
| **Set By**   | Tester                           | Manager / Product Owner / Dev Lead     |
| **Based On** | Technical impact                 | Business impact / Urgency              |
| **Answers**  | “How bad is the problem?”        | “How soon should it be fixed?”         |
| **Type**     | System stability / functionality | Business or customer-facing importance |

---

## 📌 **Severity vs Priority**

| **Severity**                                      | **Priority**                                                    |
| ------------------------------------------------- | --------------------------------------------------------------- |
| Measures the **impact** of the bug on the system. | Indicates **how urgently** the bug should be fixed.             |
| Set by the **tester**.                            | Set by **project manager**, **product owner**, or **dev lead**. |
| Technical measure.                                | Business-driven measure.                                        |
| Answers: “**How bad is it?**”                     | Answers: “**How soon should we fix it?**”                       |

---

## 🧩 **Severity Levels (Common)**

1. **Critical (Showstopper)**
   *System crash, data loss, no workaround.*

2. **High (Major)**
   *Core feature broken, difficult workaround.*

3. **Medium (Normal)**
   *Functionality issue with an easy workaround.*

4. **Low (Minor / Cosmetic)**
   *UI issues, spelling errors, not affecting functionality.*

---

## ⏰ **Priority Levels (Common)**

1. **P1 – High**
   *Must be fixed immediately (before release).*

2. **P2 – Medium**
   *Should be fixed soon, but not urgently.*

3. **P3 – Low**
   *Can be fixed later or in future releases.*

---

## ✅ **Examples to Understand Severity vs Priority**

### 🔴 **Example 1: High Severity, High Priority**

**Bug**: Application crashes when clicking “Login”.

* **Severity**: Critical (core functionality broken)
* **Priority**: High (must be fixed before any further testing or release)

---

### 🟠 **Example 2: High Severity, Low Priority**

**Bug**: Application crashes in an old browser (e.g., IE10).

* **Severity**: High (crash = major issue)
* **Priority**: Low (business no longer supports IE10)

---

### 🟡 **Example 3: Low Severity, High Priority**

**Bug**: Company name is misspelled on the homepage.

* **Severity**: Low (doesn’t affect functionality)
* **Priority**: High (branding and trust issue)

---

### 🟢 **Example 4: Low Severity, Low Priority**

**Bug**: UI element misaligned on a settings page visible only to admins.

* **Severity**: Low (cosmetic)
* **Priority**: Low (low visibility and impact)

---

## 📊 **Summary Table**

| **Bug Description**        | **Severity** | **Priority** | **Reason**                           |
| -------------------------- | ------------ | ------------ | ------------------------------------ |
| App crashes on login       | High         | High         | Stops users from using the app       |
| App crashes on old browser | High         | Low          | Rare use case, not business-critical |
| Company name misspelled    | Low          | High         | Impacts brand reputation             |
| Text overlapping in footer | Low          | Low          | Cosmetic, rarely visible page        |

---

## 👥 **Who Sets What?**

* **Tester**: Assigns **Severity** based on **technical impact**.
* **Product Owner / Manager**: Assigns **Priority** based on **business urgency**.

---

## 💡 **Pro Tip for Testers**

Always **justify your severity rating** with:

* ✅ Steps to reproduce
* ✅ Screenshots / logs
* ✅ Expected vs actual behavior
* ✅ Business impact (if known)

---
