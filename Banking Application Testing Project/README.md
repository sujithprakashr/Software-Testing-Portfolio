# 🏦 Parabank – QA Testing Project  

## 📌 Project Overview  
This project demonstrates end-to-end manual testing of the Parabank Demo online banking application. The goal was to validate core banking functionalities, identify functional and UI defects, and document complete test execution cycles using a structured QA process.

This project covers real-world banking scenarios such as account management, fund transfers, bill payments, and profile updates.

---

## 🎯 Objectives  

- Validate critical banking workflows  
- Identify functional, UI, and validation defects  
- Perform positive and negative scenario testing  
- Document defects with proper severity and priority  
- Execute structured test cycles using TestRail format  

---

## 🧪 Testing Scope  

The following modules were tested:

- ✅ User Registration  
- ✅ Login & Logout  
- ✅ Account Overview  
- ✅ Fund Transfer  
- ✅ Bill Payment  
- ✅ Profile Update  
- ✅ Session Handling  
- ✅ Negative Balance Handling  
- ✅ Input Validation  

---

## 🛠️ Testing Types Performed  

- Functional Testing  
- UI Testing  
- Boundary Value Testing  
- Negative Testing  
- Validation Testing  
- Session Testing  
- Concurrent Transaction Testing  

---

## 🐞 Sample Critical Defects Identified  

- ❌ Transfer successful even when balance is insufficient (Negative balance issue)  
- ❌ Bill payment allowed with amount exceeding available balance  
- ❌ Profile updates saved with invalid phone number and ZIP code  
- ❌ Concurrent transfers from multiple tabs deducted amount twice  

---

## 📊 Test Execution Summary  

| Metric | Count |
|--------|-------|
| Total Test Cases | 37 |
| Passed | 32 |
| Failed | 5 |
| Blocked | 0 |
| Overall Status | Completed |

---

## 🧠 Key Learnings  

- Importance of negative testing in financial applications  
- Need for strong backend validation in banking systems  
- Handling concurrency issues in transaction systems  
- Session and security validation best practices  

---

## 🚀 Tools Used  

- TestRail (Test Case Management Format)   
- Browser DevTools  
- Manual Testing Techniques  

---

## 👨‍💻 Author  

**Sujith Prakash Rudrapati**  
