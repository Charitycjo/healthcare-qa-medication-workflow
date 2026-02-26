# Defect Summary – Healthcare Medication Workflow

The following defects were identified during functional and security testing of the medication ordering workflow.

## DEF_MED_001 – Dosage Safety Validation Failure
Severity: High  
Description: System allows medication submission exceeding safe dosage limits.

## DEF_MED_002 – Unauthorized Access to Medication Ordering
Severity: Critical  
Description: Billing staff user was able to submit medication order without required privileges.

## DEF_MED_003 – Audit Log Missing Medication Name
Severity: Medium  
Description: Audit log entry created without capturing medication name field.
