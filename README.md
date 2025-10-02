# 🧸 Botium Toys – Controls & Compliance Audit  

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Audit-blue?style=for-the-badge&logo=hackthebox&logoColor=white)  
![Controls](https://img.shields.io/badge/Controls-Assessment-green?style=for-the-badge&logo=datadog&logoColor=white)  
![Compliance](https://img.shields.io/badge/Compliance-Checklist-orange?style=for-the-badge&logo=securityscorecard&logoColor=white)  

---

## 📖 About this Project  
This repository contains a **Controls and Compliance Checklist** for **Botium Toys**, created as part of a cybersecurity risk assessment exercise.  

- 🔍 Scope: Review of Botium Toys’ assets, controls, and compliance posture  
- 🎯 Goal: Identify missing controls and align with industry frameworks (PCI DSS, GDPR, SOC 1/SOC 2)  
- 📊 Risk Score: **8/10 (High)**  

---

## ✅ Controls Assessment (Summary)

- ❌ **Least Privilege** – All employees currently have access to sensitive data.  
- ❌ **Disaster Recovery Plans** – None in place.  
- ✔ **Password Policy (but weak)** – Exists, but outdated.  
- ❌ **Separation of Duties** – Not implemented.  
- ✔ **Firewall** – Configured with rules.  
- ❌ **IDS** – Not deployed.  
- ❌ **Backups** – None in place.  
- ✔ **Antivirus** – Installed and monitored.  
- ❌ **Legacy Monitoring** – Manual, no schedule.  
- ❌ **Encryption** – Not used for cardholder/customer data.  
- ❌ **Password Management** – None.  
- ✔ **Locks** – Offices, storefront, and warehouse secure.  
- ✔ **CCTV** – Surveillance in place.  
- ✔ **Fire Detection** – Alarms and prevention systems installed.  

---

## 📋 Compliance Assessment (Summary)

### PCI DSS
- ❌ Restrict cardholder access  
- ❌ Secure storage/processing  
- ❌ Encryption of card data  
- ❌ Secure password management  

### GDPR
- ✔ Protect EU customer data  
- ✔ 72-hour breach notification plan  
- ❌ Data classification & inventory  
- ✔ Privacy policies enforced  

### SOC 1 / SOC 2
- ❌ No access control policies  
- ❌ Sensitive data not restricted  
- ✔ Data integrity ensured  
- ✔ Data availability ensured  

---

## 🛠 Recommendations

Based on the **risk score of 8/10**, Botium Toys should **immediately prioritize**:  

1. **Access Control** – Implement least privilege & separation of duties.  
2. **Disaster Recovery** – Develop a recovery plan & enable automated backups.  
3. **Data Protection** – Encrypt customer/credit card data; adopt password manager; enforce stronger password rules.  
4. **Monitoring** – Deploy IDS; schedule legacy system monitoring.  
5. **Compliance Alignment** – Classify/inventory data for GDPR; restrict PCI DSS cardholder access.  

---

## 📑 Full Report  

➡️ [Download Full Checklist PDF](./Botium%20Toys%20Checklist.pdf)  

---

## ✨ Notes  
This project demonstrates my ability to:  
- Assess existing security controls  
- Identify compliance gaps (PCI DSS, GDPR, SOC)  
- Provide actionable recommendations for improving security posture  

📌 *This is a sample audit exercise created for educational purposes.*  
