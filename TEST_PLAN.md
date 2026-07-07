# TEST PLAN: TutorialsNinja Web Application

**PREPARED BY:** Ntiyiso Moraba  
**ROLE:** Test Lead  
**DATE:** 07 July 2026  

---

## 1. Overview
As part of the project engineering lifecycle, the QA team has been engaged to test specific user functionalities of the [TutorialsNinja Demo Web Application](https://tutorialsninja.com/demo). This document serves as the high-level test strategic blueprint detailing the scope, strategy, environments, and execution timelines.

---

## 2. Scope Matrix

### 📥 Inclusions (In Scope)
The functional verification will target the following core modules:
*   User Management (Register, Login, Logout, Forgot Password, My Account, Order History, Downloads)
*   Product & Discovery (Search, Product Compare, Product Display Page, Category Page)
*   Commerce Flow (Add to Cart, Wishlist, Shopping Cart Page, Checkout Page, Currencies)
*   Site Infrastructure (Home Page, Contact Us Page, Menu Options, Footer Options)

### 📤 Exclusions (Out of Scope)
*   Any system features not explicitly outlined in the inclusions list.
*   Third-party external payment processing gateways.

---

## 3. Test Environment
Simultaneous multi-platform testing will be conducted across the following matrix:
*   **Desktop OS:** Windows 10 (Chrome, Firefox, Edge) | macOS (Safari) | Linux Ubuntu (Firefox)
*   **Mobile OS:** Android (Chrome) | iOS iPhone (Safari)

---

## 4. Test Strategy & Methodologies

### Step 1: Design & Matrix Creation
We will implement industry-standard Test Design Techniques to maximize defect coverage:
*   **Black-Box Techniques:** Equivalence Class Partitioning, Boundary Value Analysis, Decision Table Testing, State Transition Testing, Use Case Testing.
*   **Heuristic Techniques:** Error Guessing, Exploratory Testing.
*   **Prioritization:** Test cases will be prioritized based on risk and critical user pathways.

### Step 2: Execution & Defect Cycles
1.  **Smoke Testing:** Conducted immediately upon build receipt. If smoke tests fail, the build is rejected, and testing is suspended until a stable build is provided.
2.  **Deep-Dive Testing:** Executed concurrently across target environments by multiple resources once smoke checks pass.
3.  **Core Testing Types:** Smoke Testing, Regression Testing & Retesting, Usability, UI, and Accessibility Testing.
4.  **Reporting:** Anomalies encountered daily will be logged and communicated via end-of-day status emails.

### Step 3: Engineering Best Practices
*   **Context-Driven Testing:** Testing strategies tailored directly to this project's unique constraints.
*   **Shift-Left Testing:** Involving QA early in the development lifecycle to mitigate bugs early.
*   **End-to-End Flow Testing:** Simulating complete customer journeys across multiple modules.

---

## 5. Problem Tracking & Logging Procedures
*   **Anomalies:** Any deviation from expected behavior will be logged. Items needing validation will be flagged as issues or questions.
*   **Reproducibility:** Upon identifying a defect, steps to reproduce and LightShot screenshots will be documented to verify reproducibility.
*   **Artifact Documentation:** 
    *   Defects will be compiled dynamically in a structural Word Document tracker.
    *   Test cases will be mapped and executed within an Excel Spreadsheet Matrix.

---

## 6. Roles & Responsibilities

| Name | Role | Core Responsibilities |
| :--- | :--- | :--- |
| **AR Barron** | Test Manager | Operational executions, commercial updates, and pricing negotiations. |
| **Ntiyiso Moraba** | Test Lead | Author test plan; obtain client sign-offs; build, coordinate, and execute test cases; validate and report defects; deliver daily summary logs. |
| **John Bown** | Senior Lead Manager | Build test scenarios; execute test cases; report application defects. |
| **Kate Smith** | Test Engineer | Interact with the application; execute planned test suites; log defects. |

---

## 7. Test Schedule & Key Milestones

### Operational Timeline
*   **July 07, 2026:** Creating Test Plan Architecture
*   **July 08, 2026:** Test Scenario & Initial Matrix Mapping
*   **July 09, 2026:** Granular Test Case Scripting
*   **July 11, 2026:** Test Execution Cycle Activation
*   **July 12, 2026:** Summary Report Compilations & Submissions

### Project Deliverables Tracker

| Deliverable | Description | Owner | Target Completion |
| :--- | :--- | :--- | :--- |
| **Test Plan** | Strategy, scope, schedule, and resource details. | Test Lead | July 14, 2026 |
| **Functional Test Cases** | Executable scripts mapped to scope requirements. | Test Lead | July 17, 2026 |
| **Defect Reports** | Daily documented bugs with reproduction steps/images. | Test Lead | Daily (n/a) |
| **Summary Report** | Metrics of bugs by area, priority, and resolution status. | Test Lead | July 20, 2026 |

---

## 8. Gate Criteria (Entry & Exit Rules)

*   **Requirement Analysis:**
    *   *Entry:* Receipt of requirements documents/project details.
    *   *Exit:* Requirements comprehensively explored, understood, and clarified.
*   **Test Planning:**
    *   *Entry:* Testable requirements established.
    *   *Exit:* Test Plan document officially signed-off by the client.
*   **Test Designing:**
    *   *Entry:* Approved Test Plan document.
    *   *Exit:* Scenarios and Test Case matrices approved by the client.
*   **Test Execution:**
    *   *Entry:* Approved test scripts; stable application build deployed.
    *   *Exit:* Test execution logs and detailed defect reports complete.
*   **Test Closure:**
    *   *Entry:* Completed execution cycles and open defect resolutions reviewed.
    *   *Exit:* Definitive Test Summary Reports finalized.

---

## 9. Suspension, Tools, & Risk Management

### Suspension & Resumption
Testing operations will ramp up, ramp down, suspend, or resume dynamically based strictly on client directives and system build stability.

### Tooling Stack
*   **Defect Tracking:** Zoho Bug Tracking Tool
*   **Visualization:** Mind Map Tool
*   **Documentation:** Microsoft Word, Microsoft Excel
*   **Media Capture:** LightShot Screenshot Tool

### Risk Mitigation Strategy
*   **Risk: Resource Unavailability** -> *Mitigation:* Pre-emptively plan backup shadow resources.
*   **Risk: Build URL Inaccessible** -> *Mitigation:* Shift focus to unexecuted test design, verification, or alternative project modules.
*   **Risk: Compressed Testing Window** -> *Mitigation:* Dynamically ramp up engineering resources based on real-time client demand.

---

## 10. Approvals
Progressing past key milestones (Test Plan, Scenarios, Test Cases, Final Reports) remains strictly gated by explicit client approval loops.
