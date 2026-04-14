# RCM Release Notes – March/April 2026

![Version](https://img.shields.io/badge/version-v2026.04-blue)
![Release Date](https://img.shields.io/badge/release-April%202026-green)
![Status](https://img.shields.io/badge/status-stable-brightgreen)
![Product](https://img.shields.io/badge/product-RCM-orange)

---

## Summary
The main focus was on enhancing public sector integrations, improving claims scrubbing capabilities for better accuracy and usability, and expanding auto remarks functionality to support more flexible and accurate workflows.

---

## Public Sector Integration
- Introduced a 360-degree view of patient visits, providing full visibility into insurance, eligibility, pre-authorization, and claim generation for seamless visit tracking
- Enabled creation of physicians in WRCM based on incoming integration data directly through the RCM UI
- Enabled viewing and uploading of physician and provider lists directly through the RCM UI
- Introduced a provider configuration page to simplify public sector providers' integration setup
- Soft release of KFMC’s evening clinic feature
- Introduced support for oncology case identification and management within inpatient workflows

---

## Scrubbing
- Added a filter on department, patient type (inpatient/outpatient/emergency), and doctor
- Reduced unnecessary services information from the claim page, showing only non-standard or standard descriptions
- Reordered services in the claim page
- Enhanced claims Excel file
- Added OTD validation for claims
- Enhanced visibility of linked claim data (same episode number), including services, OTD, technical validation remarks, and doctor’s remarks

---

## Auto Remarks (Smart Audit)
- Separated auto remarks into Technical and Medical categories
- Added flexibility to enable Technical, Medical, or both validations based on customer needs
- Enhanced batch view to display detailed information for each processed batch
- Expanded integrations to improve automated remark generation
- Introduced an endpoint to allow auto remarks utilization by other products

---

## Technical & Platform Updates
- Released a new version of the Angular-based UI application, upgraded to the latest framework version, and integrated with Keycloak for authentication
- Currently operating in a dual setup where the legacy application continues to support existing modules, while new modules are being developed and deployed on the upgraded application
- Introduced a new API gateway integrated with Keycloak, running alongside the existing gateway to ensure backward compatibility during the transition phase

---

## Impact
Improved operational efficiency and audit accuracy through enhanced claims visibility, smarter validations, and automation—enabling faster processing, reduced manual effort, and better control for operations teams and claims auditors.

---

## Action Required
No immediate action is required.
