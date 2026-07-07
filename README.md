# 🏨 Shady Meadows B&B - Quality Assurance Portfolio

![QA Status](https://img.shields.io/badge/QA_Status-Completed-success)
![Testing Type](https://img.shields.io/badge/Testing-Manual_UI_%26_Functional-blue)
![Tools](https://img.shields.io/badge/Tools-Jira_%7C_Zephyr_Scale-orange)

## 📌 Project Overview
This repository contains a comprehensive **End-to-End Manual Testing** lifecycle for the **Shady Meadows Bed & Breakfast** web application (a known QA testing sandbox: `automationintesting.online`). 

The primary objective of this project is to demonstrate industry-standard Software Quality Assurance methodologies, including requirement analysis, test planning, scenario design, and strict defect tracking.

## 🛠️ Tech Stack & QA Tools
* **Target Environment:** Web UI (Sandbox)
* **Test Case Management:** Zephyr Scale
* **Defect Tracking:** Jira (Simulated via Markdown Logs)
* **Version Control:** Git & GitHub
* **Methodologies:** Black Box Testing, Boundary Value Analysis (BVA), Error Guessing, UI/UX Verification, and Forced Browsing (Security Testing).

## 📂 Repository Structure
*This repository is organized logically to reflect a standard enterprise QA workflow.*

* **📁 1_Closure/**
* `Test_Closure_Report.md` - Final execution metrics and release decisioning.
* **📁 2_Defect_Tracking/**
  * `Bug_Report.md` - Defect tracking log documenting 5 identified bugs (including 2 Critical systemic crashes) mapped with accurate reproduction steps.
* **📁 3_Requirements/**
  * `frs.docx` - Functional Requirement Specification detailing the scope, business rules, and the Global Data Dictionary.
* **📁 4_Test_Design/**
  * `TestScenario_Original.csv` - 13 high-level test scenarios covering complete core functionality.
  * `TestCase_Original.csv` - 33 precisely mapped test cases executing both positive (Happy Path) and negative boundary flows.
* **📁 5_Test_Planning/**
  * `TestPlan_ShadyMeadows.docx` - Master Test Plan outlining the test strategy, in-scope/out-of-scope modules, and entry/exit criteria.

## 📊 Key Highlights & Metrics
* **Total Test Cases Executed:** 33
* **Functional Coverage:** 100% against the FRS
* **Defects Logged:** 5 (2 Critical Blockers, 3 Major UI/Logic gaps)
* **Release Recommendation:** **NO-GO** (Pending resolution of blocker defects within the booking engine).

## 👤 Author
**Farzan Ahmad**  
*Software Quality Assurance Engineer*  
Dedicated to delivering bug-free user experiences through meticulous documentation, logical test design, and transparent defect reporting.