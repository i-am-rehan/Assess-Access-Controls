# 🔒 Assess Access Controls – Payroll Incident Investigation

## 📌 Overview
Investigated a payroll security incident at a growing business where a deposit was nearly transferred to an unauthorized bank account. The objective was to determine how the incident occurred, identify weaknesses in access controls, and recommend mitigations to prevent recurrence.

---

## 🕵️ Incident Analysis
- **Event Log Review:**  
  - Detected login activity outside normal business hours.  
  - Login attempt originated from an unfamiliar IP address.  

- **Employee Directory Cross-Check:**  
  - Identified that the account used belonged to a former employee.  
  - Access was still active despite the employee’s departure.  

---

## ⚠️ Key Issues Identified
1. **Shared Accounts:** Company resources were managed through a shared cloud drive.  
2. **Inactive Account Exploitation:** Former employee account was not deactivated and remained accessible.  

---

## 🛡️ Recommendations
To reduce risk and strengthen access controls, the following mitigations were proposed:

- **Role-Based Access Control (RBAC):** Assign permissions according to job responsibilities, eliminating shared accounts.  
- **Account Deprovisioning Policy:** Immediately disable and remove access for employees who leave the company.  
- **Multi-Factor Authentication (MFA):** Add an extra layer of verification to block unauthorized access even if passwords are stolen.  
- **Regular Access Reviews:** Conduct periodic audits of accounts and permissions to ensure compliance with least privilege principles.  

---

## ✅ Outcome
The investigation revealed that poor access control practices—particularly reliance on shared accounts and failure to deactivate former employees—were directly responsible for the incident. By implementing RBAC, MFA, and structured offboarding processes, the business can significantly reduce the likelihood of unauthorized transactions and insider threats.

---

## 📄 Supporting Documents
- [Access Controls Worksheet →](https://docs.google.com/document/d/1waBIheWuPgaEAB78xtjK6b88SMnZ9wwccmWih0gkepE/edit?usp=sharing)  
- [Accounting Exercise →](https://docs.google.com/spreadsheets/d/1Ws7kDQgow_odtooXqZOhXyIxNfBxwtVlYeDV1L09PCw/edit?usp=sharing)
