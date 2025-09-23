# Security Audit Overview – Botium Toys

## Audit Scope and Goals
The scope of this audit covered the entire security program at **Botium Toys**, including on-premises equipment, employee devices, internal networks, data retention systems, and legacy environments. The primary goals of this audit were:  
- To identify existing assets and evaluate security controls currently in place.  
- To assess compliance with key regulatory frameworks including **PCI DSS, GDPR, and SOC 1/2**.  
- To provide actionable recommendations to reduce risk exposure and improve Botium Toys’ overall security posture.  

---

## Current Assets Reviewed
- On-premises infrastructure supporting in-office operations.  
- Employee equipment (desktops, laptops, smartphones, headsets, accessories).  
- Internal network and internet infrastructure.  
- Systems/software: accounting, telecom, database, inventory management, e-commerce.  
- Customer data storage and local databases.  
- Legacy systems requiring manual monitoring and intervention.  
- Physical security measures: CCTV, locks, fire prevention systems.  

---

## Risk Assessment Summary
- **Risk Score:** 8/10 (High)  
- **Key Risk Drivers:** Inadequate controls for access, encryption, and disaster recovery, along with limited compliance to industry/governmental regulations.  
- **Impact:** Medium risk to asset availability and data integrity; **high regulatory and reputational risk** due to customer data exposure.  

---

## Control Findings
### Implemented Controls
- Firewall protections in place.  
- Antivirus software regularly updated and monitored.  
- Physical access controls: locks, CCTV surveillance, and fire safety equipment.  
- Basic password policy (though currently insufficient).  
- Breach notification plan established for EU customers.  

### Missing or Insufficient Controls
- Encryption for credit card data and sensitive PII/SPII.  
- Principle of least privilege and separation of duties.  
- Intrusion Detection System (IDS).  
- Documented disaster recovery and backup plans.  
- Centralized password management system.  
- Regular, structured maintenance schedule for legacy systems.  

---

## Compliance Review
### PCI DSS
- Missing encryption of customer financial data.  
- Inadequate restriction of access to cardholder information.  
- Weak password policy and absence of centralized management.  

### GDPR
- Breach notification policy in place, but gaps in:  
  - Data classification/inventory.  
  - Broader enforcement of privacy policies beyond the IT team.  

### SOC Type 1 and 2
- Access policies not fully formalized.  
- Data integrity largely ensured, but monitoring needs strengthening.  
- Business continuity and availability not well supported (due to lack of backups/DRP).  

---

## Recommendations
### High Priority (1–3 months)
- Implement encryption across all systems where customer data is stored, processed, or transmitted.  
- Enforce access controls through least privilege and separation of duties.  
- Roll out a centralized password management system with stronger complexity requirements.  
- Develop and document a disaster recovery plan with regular data backups.  

### Medium Priority (3–6 months)
- Deploy an IDS for real-time detection of unauthorized activity.  
- Schedule structured maintenance for legacy systems.  
- Improve compliance reporting and audit readiness.  

### Ongoing Improvements
- Continue regular monitoring of antivirus and firewall controls.  
- Maintain physical security investments (locks, CCTV, fire safety).  

---

## Conclusion
Botium Toys maintains fundamental physical and technical controls but faces **urgent risks in data protection and compliance**. By prioritizing encryption, access rights, backups, and compliance-oriented policies, Botium Toys can significantly reduce its risk score and strengthen its security posture, ensuring both regulatory compliance and customer trust.
