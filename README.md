# QA Engineering Projects Portfolio  

This portfolio highlights the projects I completed during the **TripleTen QA Engineering Bootcamp**.  
Each sprint demonstrates progression from **manual testing → API → database → mobile → automation with Python, Selenium, and POM**.  

---

## Sprint 1 — Urban Routes: Bug Reports in Jira  
**Platform:** Web App (Urban Routes), Jira  
**Focus:** Manual exploratory testing + structured bug reporting.  

**Key Deliverables:**  
- Tested route-building and cost calculation features  
- Reported bugs in Jira using summary, description, steps to reproduce, expected vs. actual results  
- Captured browser/OS environment for reproducibility  

**Evidence:** 📂 Jira Project Board (Sprint 1)  
**Additional Evidence:** 📂 [Google Drive (All Projects)](https://drive.google.com/drive/folders/10c1yiXWxxvxvGhwz4A6iF-qZ_fyullpm?usp=share_link)  

---

## Sprint 2 — Requirement Analysis & Test Design  
**Platform:** Urban Routes (Web App), Google Docs/Sheets  
**Focus:** Test design using equivalence partitioning (EC) + boundary value analysis (BVA).  

**Key Deliverables:**  
- Decomposed FR-1 to FR-4 into atomic blocks  
- Created equivalence class + boundary value partitions  
- Designed positive/negative test cases in Google Sheets  
- Linked test failures to Jira bug reports  

**Evidence:** 📂 Sprint 2 Google Drive Folder  

---

## Sprint 3 — Urban Routes: DevTools & Complex Features  
**Platform:** Chrome DevTools, Jira, Google Sheets  
**Focus:** Combined requirement analysis + DevTools testing.  

**Key Deliverables:**  
- Decomposed Carsharing (FR-CS32, FR-CS33) + Aero Taxi (FR-AT4, FR-AT6) requirements  
- Built EC + BVA test cases  
- Verified responses and simulated overrides in DevTools  
- Logged bugs with network evidence and reproducible steps  

**Evidence:** 📂 Sprint 3 Google Drive Folder  

---

## Sprint 4 — Urban Grocers API: Kits & Fast Delivery  
**Platform:** Postman, XML, Google Sheets, Jira  
**Focus:** API test design & execution.  

**Key Deliverables:**  
- **Requirement 1 (Kits):** 14–20 test cases for `/api/v1/kits/:id/products`  
  - Kit ID validation (200 vs 404)  
  - Product ID validation (valid vs non-existent → 400)  
  - Quantity & body structure validation  
- **Requirement 2 (Fast Delivery XML):** 19–28 test cases for `/fast-delivery/v3.1.1/calculate-delivery.xml`  
  - Delivery time boundary testing vs operating hours  
  - Product weight & count edge cases  
- Bug reports with HTTP method, endpoint, and status code in titles  

**Evidence:** 📄 [Sprint 4 Google Sheets Submission](https://docs.google.com/spreadsheets/d/1ZZraSr_65qMXobSshkjoaxbP2ZvL70asP6Fcbx59VPs/edit?usp=share_link)  
**Additional Evidence:** 📂 Google Drive Folder  

---

## Sprint 5 — Console & Database Testing  
**Platform:** Linux CLI, SQL (PostgreSQL)  
**Focus:** Backend log analysis + database validation.  

**Key Deliverables (High-Level):**  
- Analyzed server logs with Linux command line tools  
- Filtered error logs into categories (400 vs 500)  
- Ran SQL queries to validate taxi fleet data and company sizes  

**Evidence:** 📄 [Sprint 5 Google Doc Submission](https://docs.google.com/document/d/1wcc2aoDZV_jqOOV8h8HobtS8LpbkCkbtYmexGxxA1pA/edit?usp=share_link)  

--
## Sprint 6 — Urban Lunch Mobile App Testing  
**Platform:** Android Emulator (Pixel 5), Figma, Google Sheets, Jira  
**Focus:** Functional mobile testing.  

**Key Deliverables:**  
- Built test checklist for ordering flow based on requirements  
- Installed & executed Urban Lunch app tests in emulator  
- Logged failed tests with Jira bug reports + evidence  
- Delivered test execution report with PASSED/FAILED results  

**Evidence:** 📄 [Sprint 6 Google Sheets Submission](https://docs.google.com/spreadsheets/d/14kCn6mjNKNp0YaLSDbCLj1nN8i04XfBU8n9kRN5h1gU/edit?usp=share_link)  

---

## Sprint 7 — Python Automation Framework Setup  
**Platform:** Python, PyTest, Selenium (prep)  
**Focus:** Laying groundwork for automation.  

**Key Deliverables:**  
- Created modular repo: `data.py`, `helpers.py`, `main.py`, `requirements.txt`  
- Added test data constants (address, phone, card, driver message)  
- Defined 8 placeholder test functions in `main.py` (PyTest-compatible)  
- Added `setup_class` for server connectivity checks  
- Prepared loop for “Order 2 Ice Creams” test  

**Evidence:** 📂 [Sprint 7 GitHub Repo](https://github.com/CelestRW/QA-USA-Python_Automation)  

---

## Sprint 8 — Selenium End-to-End Automation (Urban Routes)  
**Platform:** Python, Selenium WebDriver, PyTest, POM  
**Focus:** Full automation of Urban Routes app.  

**Key Deliverables:**  
- Implemented **Page Object Model (POM)** in `pages.py`  
- Automated end-to-end flow:  
  - Set route → Select tariff → Enter phone → Verify SMS → Add card → Add driver comment → Order blanket & handkerchiefs → Order 2 ice creams → Verify car search modal  
- Used explicit waits, conditional checks, and helper utilities  
- Structured tests in `main.py`, locators + methods in `pages.py`  

**Evidence:** 📂 [Sprint 8 GitHub Repo (urban-routes-project)](https://github.com/CelestRW/urban-routes-project)  

---

## Sprint 9 — Final Project: Urban Scooter (Web, Mobile, API)  
**Platform:** Chrome, Opera, Android Studio, Postman, Jira, Google Sheets  
**Scope:** Capstone project validating Urban Scooter across Web, Mobile, and API layers.  

**Key Deliverables:**  
- **Web App (Task 1):** Designed + executed test cases for About Customer form (name & phone) across Chrome/Opera. Logged bugs in Jira.  
- **Mobile App (Task 2):** Installed app in emulator, created courier via API, tested highlighted features in Figma. Logged defects in Jira.  
- **API Backend (Task 3):** Designed + executed test cases for Add/Delete Courier endpoints. Validated response codes (200, 400, 404) and error handling in Postman.  
- Consolidated results in Google Sheets with Jira bug links.  

**Evidence:** 📄 [Sprint 9 Google Sheets Submission](https://docs.google.com/spreadsheets/d/1kpN3wpZi5FjRwxllWBb_rm5mLtDuL5zI_Ft6l-scwkM/edit?usp=share_link)  

---
