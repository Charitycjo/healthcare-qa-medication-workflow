# Test Scenarios – Healthcare Medication Order Workflow

This document outlines high-level test scenarios validating the end-to-end medication ordering workflow within a simulated healthcare system.

---

## 1. Patient Search

TS_MED_001 – Validate patient search using valid patient ID  
TS_MED_002 – Validate patient search using patient full name  
TS_MED_003 – Validate system response when patient does not exist  
TS_MED_004 – Validate required search field enforcement  

---

## 2. Medication Ordering

TS_MED_005 – Validate successful medication order submission  
TS_MED_006 – Validate prevention of order submission without medication selection  
TS_MED_007 – Validate dosage safety limit enforcement  
TS_MED_008 – Validate dosage format validation  

---

## 3. Allergy & Safety Checks

TS_MED_009 – Validate allergy conflict alert during medication ordering  
TS_MED_010 – Validate physician override workflow for allergy warning  

---

## 4. Pharmacy Verification

TS_MED_011 – Validate pharmacist approval of medication order  
TS_MED_012 – Validate pharmacist rejection of medication order  
TS_MED_013 – Validate required status selection before pharmacist submission  
TS_MED_014 – Validate display of pending medication orders in queue  

---

## 5. Order Completion

TS_MED_015 – Validate completion of verified medication order  
TS_MED_016 – Validate cancellation of medication order from pharmacy queue  

---

## 6. Security & Access Control

TS_MED_017 – Validate access restriction for unauthorized users  
TS_MED_018 – Validate system behavior during session timeout while entering medication order  

---

## 7. Data Integrity & Audit Logging

TS_MED_019 – Validate medication persistence in patient profile after submission  
TS_MED_020 – Validate audit log creation for medication order activity  

---

## 8. UI / Usability

TS_MED_021 – Validate medication search autocomplete functionality
