# OpenCart (Frontend) - Test Plan

### Prepared by: S. Jaydev Acharya  
**Date**: March 10, 2024

---

## Table of Contents
1. [Overview](#overview)
2. [Scope](#scope)
   - [Inclusions](#inclusions)
   - [Test Environments](#test-environments)
   - [Exclusions](#exclusions)
3. [Test Strategy](#test-strategy)
4. [Defect Reporting Procedure](#defect-reporting-procedure)
5. [Roles and Responsibilities](#roles-and-responsibilities)
6. [Test Schedule](#test-schedule)
7. [Test Deliverables](#test-deliverables)
8. [Entry and Exit Criteria](#entry-and-exit-criteria)
9. [Suspension and Resumption Criteria](#suspension-and-resumption-criteria)
10. [Tools](#tools)
11. [Risks and Mitigations](#risks-and-mitigations)
12. [Approvals](#approvals)

---

## Overview

This Test Plan outlines the approach for testing the functionalities of the OpenCart web application, located at `https://demo.opencart.com/`. It details the scope, test strategy, schedule, and resources required to perform comprehensive functional testing of the defined features.

---

## Scope

The scope includes functional testing of the following features of the OpenCart web application:

### Inclusions:
- Register
- Login & Logout
- Forgot Password
- Search
- Product Compare
- Product Display Page
- Add to Cart
- Wish List
- Shopping Cart
- Currencies
- Home Page
- Checkout Page
- My Account Page
- Order History Page
- Downloads Page
- Contact Us Page
- Menu Options
- Footer Options
- Category Pages

### Test Environments:
- **Windows 10**: Chrome, Firefox, Edge
- **Mac OS**: Safari Browser
- **Android Mobile OS**: Chrome
- **iPhone Mobile OS**: Safari

### Exclusions:
- Features not listed under **Inclusions**
- Third-party features and Payment gateways
- Test Automation

---

## Test Strategy

The strategy involves **Functional Testing** with the following steps:

1. **Test Scenario and Case Creation**:
   - Test Design Techniques: Equivalence Class Partition, Boundary Value Analysis, Decision Table Testing, State Transition Testing, Use Case Testing
   - Additional Techniques: Error Guessing, Exploratory Testing

2. **Testing Process**:
   - Smoke Testing for initial functionality checks
   - Regression Testing, Retesting, Usability Testing, Functionality & UI Testing after receiving stable builds

3. **Best Practices**:
   - Context-Driven Testing
   - Shift Left Testing
   - Exploratory Testing
   - End-to-End Flow Testing

---

## Defect Reporting Procedure

- Any deviation from expected behavior will be reported as a defect or an observation.
- Defects will be verified for reproducibility and documented with screenshots and steps.
- Defects will be reported daily via email.
- All defects and test cases will be documented in Excel.

---

## Roles and Responsibilities

- Testing team is responsible for creating test scenarios, executing test cases, and reporting defects.

---

## Test Schedule

| Task                  | Time Duration |
|-----------------------|---------------|
| Test Plan Creation     | Start to End Date |
| Test Case Creation     | Start to End Date |
| Test Case Execution    | Start to End Date |
| Summary Report         | End Date |

---

## Test Deliverables

| Deliverable           | Description                                    | Target Date |
|-----------------------|------------------------------------------------|-------------|
| Test Plan             | Detailed scope, strategy, and schedule         | Date        |
| Functional Test Cases | Test cases for the defined scope               | Date        |
| Defect Reports        | Detailed defect descriptions, screenshots, etc.| N/A         |
| Summary Reports       | Bugs by Bug#, Functional Area, and Priority    | Date        |

---

## Entry and Exit Criteria

### Requirement Analysis
- **Entry**: Requirements documents received
- **Exit**: Requirements understood by the team

### Test Planning
- **Entry**: Testable requirements derived
- **Exit**: Test Plan signed off

### Test Designing
- **Entry**: Test Plan signed off
- **Exit**: Test Scenarios and Cases signed off

### Test Execution
- **Entry**: Test Scenarios and Cases signed off, Application ready for testing
- **Exit**: Test Reports and Defect Reports ready

### Test Closure
- **Entry**: Test Reports and Defect Reports ready
- **Exit**: Test Summary Reports completed

---

## Suspension and Resumption Criteria

- Project suspension or resumption will be based on the client's decision.
- Resources will be adjusted dynamically based on client needs.

---

## Tools

- XYZ Bug Tracking Tool
- Mind Map Tool
- Snipping Tool for screenshots
- Microsoft Word and Excel

---

## Risks and Mitigations

| Risk                        | Mitigation                                      |
|-----------------------------|-------------------------------------------------|
| Non-Availability of Resources| Backup Resource Planning                       |
| Build URL not working        | Resources will focus on other tasks            |
| Less time for Testing        | Dynamic resource ramp-up based on client needs |

---

## Approvals

- Test Plan
- Test Scenarios
- Test Cases
- Reports

Testing will proceed to the next phase only after client approval of these documents.
