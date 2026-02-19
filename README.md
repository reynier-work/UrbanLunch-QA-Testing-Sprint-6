# QA Testing Report: Urban.Lunch App - Sprint 6

**Analyst:** Reynier Martin  
**Project:** Urban.Lunch (Android Application)  
**Tools:** Android Studio, Jira, Excel

## Project Summary
This repository documents the test execution and defect reporting for the dish selection and order tracking flows. The primary objective was to ensure business logic integrity and correct UI rendering.

## Methodology and Tools
* **Android Studio Panda 1:** Utilized Layout Inspector for component hierarchy validation and Logcat for event monitoring.
* **Jira:** Defect documentation following severity and priority standards.
* **Test Design:** Execution of 47 test cases based on product requirements.

## Critical Findings
During the testing cycle, the following defects were identified:
* **Timer Logic Discrepancy:** The system displays the estimated home delivery time instead of the pickup time, contradicting the business requirement.
* **Missing UI Components:** Layout Inspector confirmed the absence of the "preparation time" text node within the Component Tree.
* **Element Overlap:** Visual defect on the details screen where the restaurant name interferes with the readability of cost and time.

## Final Test Status
* **Passed:** 42
* **Failed:** 3
* **Skipped:** 2

## Navigation Note
Checklist files, bug reports, and visual evidence are attached directly to the root of this repository to ensure easy access and information availability.

---
*Technical documentation generated for the QA Engineering portfolio.*

**Contact:** [reynierwork26@gmail.com](mailto:reynierwork26@gmail.com)
