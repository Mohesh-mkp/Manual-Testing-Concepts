## 📌 **Definition: Severity vs Priority**

| **Severity**                                      | **Priority**                                                        |
| ------------------------------------------------- | ------------------------------------------------------------------- |
| Measures the **impact** of the bug on the system. | Indicates **how urgently** the bug should be fixed.                 |
| Set by the **tester**.                            | Set by the **project manager**, **product owner**, or **dev lead**. |
| Technical measure.                                | Business-driven measure.                                            |
| Answers: “**How bad is it?**”                     | Answers: “**How soon should we fix it?**”                           |

---

## 🧩 **Severity Levels (Common)**

1. **Critical (Showstopper)**

   * System crash, data loss, no workaround.
2. **High (Major)**

   * Core feature broken, difficult workaround.
3. **Medium (Normal)**

   * Functionality issue with an easy workaround.
4. **Low (Minor/Cosmetic)**

   * UI issues, spelling errors, not affecting functionality.

---

## ⏰ **Priority Levels (Common)**

1. **P1 – High**: Must be fixed immediately (before release).
2. **P2 – Medium**: Should be fixed soon, but not urgently.
3. **P3 – Low**: Can be fixed later or in future releases.

---

## ✅ **Examples to Understand Severity vs Priority**

---

### 🔴 **Example 1: High Severity, High Priority**

**Bug**: Application crashes when clicking “Login”.

* **Severity**: Critical (core functionality broken).
* **Priority**: High (must be fixed before any further testing or release).

---

### 🟠 **Example 2: High Severity, Low Priority**

**Bug**: Application crashes in an old browser (e.g., Internet Explorer 10).

* **Severity**: High (crash = major issue).
* **Priority**: Low (business has dropped support for IE10).

---

### 🟡 **Example 3: Low Severity, High Priority**

**Bug**: Company name is misspelled on the homepage.

* **Severity**: Low (doesn’t affect functionality).
* **Priority**: High (branding issue, high visibility).

---

### 🟢 **Example 4: Low Severity, Low Priority**

**Bug**: UI element misaligned on a settings page only visible to admins.

* **Severity**: Low (cosmetic).
* **Priority**: Low (rarely used page, low visibility).

---

## 📊 Summary Table

| Bug Description            | Severity | Priority | Reason                               |
| -------------------------- | -------- | -------- | ------------------------------------ |
| App crashes on login       | High     | High     | Stops user from using the app        |
| App crashes on old browser | High     | Low      | Rare use case, non-business critical |
| Company name misspelled    | Low      | High     | Impacts brand reputation             |
| Text overlapping in footer | Low      | Low      | Cosmetic, not visible to users often |

---

## 👥 Who Sets What?

* **Tester**: Assigns **Severity** based on impact observed during testing.
* **Product Owner/Manager**: Assigns **Priority** based on business need and deadlines.

---

## 💡 Pro Tip:

If you’re a tester, always **justify severity** with:

* Steps to reproduce
* Screenshots/logs
* Expected vs. actual behavior
* Business impact (if known)

---
