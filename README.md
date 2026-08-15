# 🛒 OpenCart: Manual Testing & Bug Reporting

Welcome to my manual testing portfolio project focused on the core authentication flows of the **OpenCart** e-commerce platform. This project demonstrates structured test case design, thorough execution, and professional defect reporting for **Login** and **Sign Up** modules.

---

## 🎯 Project Scope

This testing cycle was dedicated to validating the security, functionality, and user interface of user authentication. The testing covered:
* Valid and invalid credential combinations.
* Empty field validations and error message triggers.
* Whitespace handling (leading/trailing spaces).
* UI validations including placeholder checks and layout consistency.

---

## 📊 Test Execution Summary

| Metric | Details |
| :--- | :--- |
| **Modules Tested** | Login & Sign Up |
| **Test Cases Authored** | 20 |
| **Testing Type** | Manual Black-Box Testing |
| **Documentation** | Strict formatting including Test ID, Steps, Expected vs Actual, Severity, and Priority. |

---

## 🐛 Key Bug Findings

During execution, several interesting defects were uncovered and formally documented. Here are the highlights:

* 🔴 **Critical Severity:** The system authenticated and logged in users even when an *invalid* password was provided alongside a valid email.
* 🟡 **Medium Severity:** The email input field failed to properly sanitize or handle leading and trailing spaces, causing validation issues.
* 🟢 **Low/UI Severity:** Missing placeholder text on the Password field, slightly impacting the user experience.

---

## 💡 The QA Takeaway

**Why Manual Testing Matters:** 
While automation is incredible for catching regressions, human testers catch the edge cases nobody thought to script. Small UI inconsistencies, logical loopholes, and input handling flaws often require a human perspective to identify. 

Finding the bugs is only half the job. Documenting them properly so developers can recreate and fix them efficiently is where a QA Engineer truly brings value.

---

## 📂 Repository Contents

* `Test Cases.xlsx` - Detailed suite of 20 manual test cases.
* `BugReports.xlsx` - Formal documentation of all identified defects with severity and priority rankings.
