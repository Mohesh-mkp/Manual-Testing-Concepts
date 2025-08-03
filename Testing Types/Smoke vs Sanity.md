
---

## ✅ **What is Smoke Testing?**

**Smoke Testing** is a **preliminary test** done to check whether the **basic functionalities** of a build are working or not.

* Also called: **Build Verification Testing**
* Performed: **Before** deep testing begins
* Purpose: To **accept or reject** a new build
* Done: After every new build deployment

### 🔷 Example:

In an e-commerce app, testers will:

* Check if the app launches
* Login works
* Products load
* Cart opens

If any of these fail → build is **rejected** for further testing.

---

## ✅ **What is Sanity Testing?**

**Sanity Testing** is a **narrow, focused test** done **after a bug fix or small update** to ensure that the specific functionality works and the change didn’t break anything.

* Performed: After receiving a **hotfix or minor code change**
* Purpose: To **quickly verify correctness** of a particular issue
* Scope: Small, focused area (not full regression)

### 🔷 Example:

After fixing a bug where the **"Apply Coupon"** button wasn’t working:

* Sanity test only that button
* Ensure the coupon is applied and amount updates
* Don’t test the whole checkout flow

---

## 🔁 **Key Differences Between Smoke & Sanity Testing**

| Criteria     | **Smoke Testing**                   | **Sanity Testing**                              |
| ------------ | ----------------------------------- | ----------------------------------------------- |
| Purpose      | To verify **basic build stability** | To verify **specific functionality or bug fix** |
| Performed on | New builds                          | Stable builds with minor changes                |
| Type         | Shallow and wide                    | Narrow and deep                                 |
| Who performs | QA/Testers                          | QA/Testers                                      |
| Automation   | Often automated                     | Can be manual or automated                      |
| Examples     | Login, homepage load, navigation    | Confirming a “Login issue” is resolved          |

---

## 🎯 Simple Analogy:

* **Smoke Test** = Checking if the **car starts and runs** before a full test drive.
* **Sanity Test** = Checking if the **headlights work properly** after fixing a bulb.

---
