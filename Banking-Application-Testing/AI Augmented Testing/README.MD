# 🤖 AI-Augmented Testing – Parabank QA Project  

## 📌 Overview  
This folder contains AI-assisted test cases designed to improve coverage of edge cases, concurrency risks, and security scenarios in the Parabank application. These scenarios focus on transaction reliability, session security, and system behavior under unusual or failure conditions.

AI was used to help identify high-risk scenarios, and all test cases were reviewed, structured, and executed manually.

---

## 🎯 Objectives  

- Identify edge cases not covered in standard functional testing  
- Validate transaction integrity during interruptions  
- Test system behavior under concurrent user actions  
- Evaluate input validation and system limits  
- Verify session security and access control  

---

## 🧪 Test Cases Included  

| Test Case ID | Title | Purpose |
|-------------|------|---------|
| T137 | Fund transfer submission during network interruption | Ensures system handles incomplete or interrupted transactions safely |
| T138 | Duplicate bill payment prevention on browser refresh after submission | Confirms duplicate transactions are not created on refresh |
| T139 | Large numeric value handling in transfer amount field | Validates system response to extremely large input values |
| T140 | Concurrent transfers from two tabs using the same source account | Tests transaction integrity during simultaneous actions |
| T141 | Unauthorized page access after manual session cookie deletion | Verifies session handling and access security |

---

## ▶️ Execution Status  

All AI-augmented test cases were executed manually.

**Execution Result:** ✅ Passed  

These tests confirmed system behavior under advanced and edge-case scenarios.

---

## 🚀 Testing Value  

This section demonstrates:

- Risk-based testing approach  
- AI-assisted test design workflow  
- Advanced banking transaction validation  
- Security and concurrency testing awareness  

---

## 🛠️ Tools & Methods  

- Manual Testing  
- TestRail (Test Case Management)  
- Browser DevTools (Session & Network simulation)  
- AI-assisted scenario generation  

---

## 👨‍💻 Author  

**Sujith Prakash Rudrapati**  
