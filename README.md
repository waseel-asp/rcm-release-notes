# RCM Release Notes – June 2026

![Version](https://img.shields.io/badge/version-v2026.04-blue)
![Release Date](https://img.shields.io/badge/release-April%202026-green)
![Status](https://img.shields.io/badge/status-stable-brightgreen)
![Product](https://img.shields.io/badge/product-RCM-orange)

---

# RCM Release Notes – June 2026

## Summary

### Claims Preparation and Extraction

- Developed UI pages for Claim Preparation and Claim Extraction within the RCM system.
  - Empowers the OPs team with full control over the preparation and extraction cycle.
  - Supports both **econnect** and **eclaims** platforms.
  - Eliminates dependency on the IT team for these activities.

- Added support for claim preparation using an uploaded Excel file containing a specific list of visits.

- Added support for claim extraction using an uploaded Excel file containing a specific list of claims.

- Added support for extracting claims for multiple payers in a single operation, providing a more efficient and user-friendly experience.

---

### R2 Integration

- Implemented support for **HL7 A11 Cancellation Events** in both Integration and Billing.
  - Cancelled visits are automatically marked as cancelled.
  - Prevents approval, claim, and billing generation for cancelled visits.

- Enhanced diagnosis handling by extracting diagnosis information from **ORM** messages in addition to **ADT** messages, improving diagnosis coverage across visits.

---

### Billing Enhancements

- Enhanced Beneficiary and Insurance management by allowing updates to additional fields, including adding or modifying the **Department** value.

- Added bulk actions in Items to:
  - Mark all services as **Executed**
  - Mark all services as **Not Executed**
  - Delete all services

- Enabled **DRG code upload** for bills and automatically marked other services as **Not Executed** when a new DRG is added.

- Added the ability to download bill information.

- Implemented visit type identification (Pharmacy, Laboratory, Physiotherapy, etc.) to prevent incorrect consultation billing for non-consultation visits.

---

### Evening Clinic

- Added support for updating Evening Clinic visit data by allowing:
  - Care Team additions/updates
  - Diagnosis additions/updates
  - Item additions when missing

- Added the ability to retry eligibility checks for:
  - Single visits
  - Multiple visits

---

### Scrubbing

- Implemented data masking to enhance security and protect sensitive information.

- Integrated **econnect** with the Scrubbing module to enable auditing of eConnect claims.

- Upgraded the entire Scrubbing module to:
  - Spring Boot 3
  - Java 21

  Resulting in improved performance, security, and long-term maintainability.

---

### Auto Remarks / Smart Audit

- Added audit logs to monitor and track provider actions, improving traceability and accountability.

---

## Action Required

The OPs team is requested to utilize the **Claims Preparation and Extraction** feature and share feedback on any findings to support further system stabilization and continuous improvement.

