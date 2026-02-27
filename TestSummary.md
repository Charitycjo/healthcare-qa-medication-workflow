# Test Summary Report  
Healthcare Medication Order Workflow

---

## 1. Overview

Testing was conducted on the Healthcare Medication Order Workflow system to validate functional behavior, data integrity, security controls, and workflow reliability.

Testing covered patient search, medication ordering, allergy validation, pharmacist verification, order completion, audit logging, and role-based access controls.

---

## 2. Test Execution Summary

| Metric | Count |
|--------|-------|
| Total Test Cases | 21 |
| Passed | 18 |
| Failed | 3 |
| Blocked | 0 |
| Not Executed | 0 |

---

## 3. Failed Test Cases

The following test cases failed during execution:

| Test Case ID | Description | Related Defect |
|--------------|------------|----------------|
| TC_MED_007 | Dosage exceeding safe limit not prevented | DEF_MED_001 |
| TC_MED_017 | Unauthorized user able to submit medication order | DEF_MED_002 |
| TC_MED_020 | Audit log missing medication name field | DEF_MED_003 |

---

## 4. Defect Summary

| Severity | Count |
|----------|-------|
| Critical | 1 |
| High | 1 |
| Medium | 1 |
| Low | 0 |

### Critical Defect
Unauthorized billing user able to submit medication order.

### High Defect
System allows medication dosage exceeding configured safety limit.

### Medium Defect
Audit log does not capture medication name.

---

## 5. Risk Assessment

The system presents moderate risk due to:

• Security vulnerability allowing unauthorized medication ordering  
• Safety risk related to dosage validation  
• Incomplete audit logging impacting compliance traceability  

These issues must be resolved before production deployment.

---

## 6. Conclusion

The majority of functional workflows performed as expected. However, critical security and safety defects were identified.

System is **not recommended for production release** until high and critical defects are resolved and retested.

---

## 7. QA Sign-Off

Prepared By: Charity Johnson  
Role: QA Analyst (Healthcare Domain Simulation)  
Date: [02/27/2026]
