🛒 OpenCart-Manual
<p align="center">
  <b>🔎 Manual Software Testing Project</b><br>
  <i>Requirement Analysis • Test Design • Test Execution • Defect Tracking • Traceability</i>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Testing-Manual%20Testing-1f6feb?style=for-the-badge" alt="Manual Testing">
  <img src="https://img.shields.io/badge/Methodology-Agile-2ea44f?style=for-the-badge" alt="Agile">
  <img src="https://img.shields.io/badge/Platform-OpenCart-19a974?style=for-the-badge" alt="OpenCart">
  <img src="https://img.shields.io/badge/Status-QA%20Project-f59e0b?style=for-the-badge" alt="QA Project">
</p>
> 💡 **Project at a glance:** A structured manual QA project covering the OpenCart frontend from **requirements → test scenarios → test cases → execution → defects → re-testing → regression → closure**.
---

📌 Quick Navigation  
🎯 Objectives  
📊 Project Snap shot  
🛍️ Application Overview  
🔍 Scope of Testing  
🧪 Test Scenarios  
📝 Test Case Design  
⚙️ Test Methodology  
🐞 Defect Management  
🔗 Requirement Traceability  
🖥️ Test Environment  
🧰 Testing Tools  
📂 Project Documents  
🔄 QA Workflow  
💼 Key QA Skills  

---
🎯 Objectives

The main objectives of this project are to:  
Validate the functional requirements of the OpenCart frontend.  
Verify important customer-facing e-commerce workflows.  
Design and execute manual test cases against the documen0ted
requirements.  
Identify, document, and prioritize defects.  
Maintain traceability between requirements, scenarios, test cases,
and defects.  
Validate functional behavior across supported browsers.  
Perform regression and re-testing activities for identified defects.  
Provide structured QA deliverables for the testing lifecycle.  

---
---

📊 Project Snapshot

📌 Area	📈 Coverage  
🧪 Testing Approach	Manual Testing  
🔄 Methodology	Agile / Weekly Iterations  
🗂️ Test Scenarios	8 documented scenarios  
📝 Test Cases	Scenario-based manual test coverage  
🐞 Defect Tracking	Bug Report with severity & priority    
🔗 Traceability	FRS → Scenario → Test Case → Result → Defect  
🖥️ Browser Coverage	Edge, Chrome, Firefox, Safari  
👤 Prepared By	Anvesha  

🛍️ Application Overview

OpenCart is an open-source e-commerce platform for online merchants. The
application provides a storefront through which customers can browse
products, search for products, compare products, add products to a cart,
manage their account, and complete checkout.

The FRS describes the storefront architecture and customer workflows,
including:

Home page  
Header and navigation  
Product pages  
Category product listings  
Product comparison  
Shopping cart  
Account registration and login  
Checkout  
Order confirmation  
Order history  

---

🔍 Scope of Testing

✅ In Scope  
The Test Plan identifies the following major areas for testing:  
Register Account  
Login and Logout  
Home Page  
Search  
Add to Cart  
Wish List  
Shopping Cart  
Checkout  
My Account  
Cross-browser behavior  
Functional testing  
Integration testing  
Performance testing  
Regression testing  
UAT from the tester's perspective  
Fixed-defect validation  

The Test Plan also identifies specific storefront behaviors such as
navigation, product display, category browsing, search, cart operations,
and checkout flows.  

🚫 Out of Scope

The Test Plan lists the following as out of scope:  
Database Testing  
API Testing  
Automation Testing  
Features added later  
---
🏗️ Requirements and Information Architecture  
The FRS defines the OpenCart storefront and its main customer
interaction areas.  
🏠 Home Page  
Testing includes navigation to the home page, featured products, partner
carousel behavior, header links, and navigation elements.  
📦 Product Page  
The product page includes:  
Product image and alternate views  
Product details  
Product code and availability  
Price  
Quantity selection  
Add to Cart  
Wish List  
Product Compare  
Rating and sharing  
Description  
Review tab  
🛒 Shopping Cart  
The shopping cart validates product information including:  
Product image  
Product name  
Model  
Quantity  
Unit price   
Total  
The cart also provides options for coupons, gift vouchers, shipping and
tax estimation, continuing shopping, and checkout.  
💳 Checkout  
The documented checkout process contains six steps:  
Checkout options  
Billing details  
Delivery details  
Delivery method   
Payment method  
Confirm order  
The FRS also describes successful order placement and access to order
history.

---
🧪 Test Scenarios  
The Test Scenario document contains eight primary scenarios:

Scenario ID   Scenario                                  Priority   Test Cases
---
TS_001        Verify Register Account functionality           P0           23
TS_002        Verify Login functionality                      P0           21
TS_003        Verify Logout functionality                     P0           11
TS_004        Verify Home Page Functionality                  P2            9
TS_005        Verify Checkout functionality                   P1           20
TS_006        Verify Search functionality                     P1           18
TS_007        Verify Add to Cart functionality                P1            9
TS_008        Verify My Account functionality                 P2            8
These scenarios are referenced by the test cases and linked back to the
FRS through the testing documentation.

---

🖥️ Test Environment

The Test Plan documents the following environment information:  
Operating Environment  
Windows 10  
4 GB RAM  
3.4 GHz CPU  
LAN with at least 5 Mb/s speed  
Application / Server Requirements  
The FRS identifies:  
PHP 5.4  
JavaScript  
MySQL database  
Apache web server  
Supported Browsers  
The documented browser support includes:  
Microsoft Edge  
Google Chrome  
Mozilla Firefox  
Safari  

---

🧰 Testing Tools

Activity                   Tool  
---  
Test Case Creation         Microsoft Excel  
Test Case Tracking         Microsoft Excel  
Test Case Execution        Manual  
Test Case Management       Microsoft Excel  
Defect Management          Microsoft Excel  
Test Reporting             Microsoft Excel & Jira  
Configuration Management   GitHub 

---
---
📂 Project Documents
This project is supported by the following QA artifacts:
``` text
OpenCart-Manual/  
│  
├── FRS_1(1).pdf  
├── Test_plan_1(1).pdf  
├── test_scenario_1(1).xlsx  
├── test_cases_all(1).xlsx  
├── RTM_1(1).xlsx  
├── Bug_Report_1(1).xlsx  
└── README.md

```
---
🔄 QA Workflow
``` text
FRS
 │
 ▼
Requirement Analysis
 │
 ▼
Test Scenario Design
 │
 ▼
Test Case Design
 │
 ▼
Test Data Preparation
 │
 ▼
Manual Test Execution
 │
 ├── PASS ───────────────┐
 │                       │
 └── FAIL → Bug Report   │
              │          │
              ▼          │
          Bug Fix        │
              │          │
              ▼          │
           Re-testing ───┘
              │
              ▼
       Regression Testing
              │
              ▼
       Test Reporting
              │
              ▼
          Test Closure
```
---
💼 Key QA Skills Demonstrated

This project demonstrates practical experience in:  
Manual Testing  
Functional Testing  
Integration Testing  
Regression Testing  
UAT  
Test Scenario Design  
Test Case Design  
Test Case Execution  
Test Data Preparation  
Requirement Analysis  
Requirement Traceability  
Defect Identification  
Defect Reporting  
Severity and Priority Classification  
Re-testing  
Cross-browser Testing  
Test Reporting  
Agile Testing  
QA Documentation  

---

🏆 Project Outcome  
The OpenCart-Manual project provides a structured manual QA process from
requirement analysis through test closure. The project connects the FRS
with test scenarios, detailed test cases, execution results, defect
reports, and the RTM, providing traceability across the testing
lifecycle.  

---
👤 Author  

Anvesha    
Project: OpenCart-Manual    
Role: QA / Manual Testing    
Testing Approach: Manual Testing

---

🌟 Project Highlights
> **OpenCart-Manual** demonstrates an end-to-end manual QA workflow with structured documentation and traceability.
Core QA flow:  
`📋 Requirements` → `🧠 Analysis` → `🧪 Scenarios` → `📝 Test Cases` → `▶️ Execution` → `🐞 Defects` → `🔁 Re-test` → `🔍 Regression` → `📊 Reporting` → `🏁 Closure`
<p align="center">
  <b>Built with a QA mindset ❤️</b><br>
  <i>OpenCart-Manual • Manual Testing Project • Anvesha</i>
</p>
