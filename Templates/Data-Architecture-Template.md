# Data Architecture Template

## 1. Document Information
- **Project Name:** [Insert Project Name]
- **Version:** [e.g., 1.0]
- **Date:** [Insert Date, e.g., March 25, 2025]
- **Prepared By:** [Your Name/Team]
- **Approved By:** [Stakeholder Name(s)]

## 2. Introduction
- **Purpose:** Define the data structures, storage, and flows to support the enterprise’s business processes and application systems.
- **Scope:** [Describe what’s included, e.g., “Customer and order data for e-commerce; excludes employee records.”]
- **Objectives:** 
  - [e.g., Ensure data consistency across systems]
  - [e.g., Enable real-time data access]

## 3. Architecture Overview
- **Context:** [Briefly describe the business need, e.g., “Support an integrated e-commerce platform.”]
- **High-Level Description:** [Summarize the data solution, e.g., “Centralized data warehouse with standardized entities.”]
- **Diagram:** [Placeholder for diagram—e.g., “Insert data flow or entity-relationship diagram.”]

## 4. Baseline Data Architecture
- **Current State Description:** [Describe existing data, e.g., “Customer data in spreadsheets, orders in legacy database.”]
- **Components:**
  | Data Entity       | Description                | Storage          | Status          |
  |-------------------|----------------------------|------------------|-----------------|
  | [e.g., Customer]  | [e.g., Name, address]      | [e.g., Excel]    | [e.g., Fragmented] |
  | [e.g., Order]     | [e.g., ID, date]          | [e.g., SQL DB]   | [e.g., Stable]  |
- **Issues:** [List problems, e.g., “Data silos, no standardization.”]

## 5. Target Data Architecture
- **Future State Description:** [Describe desired data, e.g., “Unified data warehouse with master data management.”]
- **Components:**
  | Data Entity       | Description                | Storage          | Standards       |
  |-------------------|----------------------------|------------------|-----------------|
  | [e.g., Customer]  | [e.g., Name, address]      | [e.g., Data Warehouse] | [e.g., MDM] |
  | [e.g., Order]     | [e.g., ID, date, status]   | [e.g., Data Warehouse] | [e.g., JSON] |
- **Benefits:** [List advantages, e.g., “Consistent data, faster reporting.”]

## 6. Gap Analysis
- **Gaps Between Baseline and Target:**
  | Gap Description             | Impact                  | Resolution             |
  |-----------------------------|-------------------------|------------------------|
  | [e.g., No central storage]  | [e.g., Data inconsistency] | [e.g., Build warehouse] |
  | [e.g., Unstandardized data] | [e.g., Reporting delays]  | [e.g., Implement MDM]  |
- **Dependencies:** [e.g., “Warehouse requires Technology Architecture updates.”]

## 7. Data Standards and Principles
- **Standards:** [List adopted standards, e.g., “ISO 8000 for data quality, SQL for queries.”]
- **Principles:** 
  - [e.g., “Single source of truth for key entities.”]
  - [e.g., “Data accessibility over security where compliant.”]

## 8. Requirements
- **Functional Requirements:** [e.g., “Store 1 million customer records.”]
- **Non-Functional Requirements:** 
  - [e.g., “Data retrieval < 2 seconds.”]
  - [e.g., “99.99% data integrity.”]

## 9. Risks and Mitigation
- **Risks:**
  | Risk                  | Likelihood | Impact   | Mitigation             |
  |-----------------------|------------|----------|------------------------|
  | [e.g., Data migration errors] | [Medium]   | [High]   | [Validate pre-migration] |
  | [e.g., Security breach] | [Low]      | [High]   | [Encrypt sensitive data] |
- **Assumptions:** [e.g., “Existing data can be cleaned within 3 months.”]

## 10. Implementation Considerations
- **Approach:** [e.g., “Migrate data in phases: customers first, then orders.”]
- **Dependencies:** [e.g., “Requires Application Architecture (Phase C) for integration.”]
- **Next Steps:** [e.g., “Design data model, select warehouse vendor.”]

## 11. Stakeholder Validation
- **Stakeholders:**
  | Name          | Role              | Concern             | Sign-Off Date |
  |---------------|-------------------|---------------------|---------------|
  | [e.g., CIO]   | [e.g., Approver]  | [e.g., Data quality]| [TBD]         |
  | [e.g., Data Lead]| [e.g., Implementer]| [e.g., Migration] | [TBD]         |

## Notes
- Use this template with `ADM/Phase-C.md` to align with TOGAF’s Data Architecture portion of Phase C.
- Customize sections based on project specifics.