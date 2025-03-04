# Requirements Management

## Purpose

The **Requirements Management** process ensures that all architectural requirements are **captured, validated, and maintained** throughout the enterprise architecture lifecycle. It acts as a **continuous process**, ensuring that evolving business needs, regulatory changes, and technological advancements are **properly integrated into architecture development**.

---
![Requirements Management](../images/TOGAF-Requirements%20Management.drawio.png)
---

## Objectives

- **Establish a structured approach** to collect, document, and manage requirements.
- **Ensure traceability** of requirements across all architecture phases.
- **Facilitate impact analysis** to assess the effect of changing requirements on architecture.
- **Maintain consistency** in aligning requirements with business goals and enterprise architecture principles.
- **Enable change management** by providing a controlled mechanism to modify requirements when necessary.

---

## Approach

Requirements Management is **a central process in the TOGAF ADM** that interacts with **all phases** of the architecture lifecycle. As business needs evolve, this phase ensures that changes are **evaluated, prioritized, and integrated without disrupting architectural integrity**.

- Requirements are **identified** and **analyzed** during early ADM phases.
- Requirements are **validated and refined** in later ADM phases.
- New or modified requirements **feed back** into architecture development for continuous improvement.

---

## Steps

### 1. Capture Business and IT Requirements
- **What:** Identify **functional, non-functional, business, and compliance requirements** from stakeholders.
- **Example:** A **banking institution** defines a requirement for **real-time fraud detection** in online transactions.

### 2. Validate and Prioritize Requirements
- **What:** Assess **feasibility, impact, and alignment with business goals**.
- **Example:** A **healthcare provider** prioritizes **HIPAA compliance and patient data encryption** over UI design improvements.

### 3. Store and Maintain Requirements Repository
- **What:** Centralize **all requirements in a structured repository** for tracking and version control.
- **Example:** A **telecommunications company** uses **Jira and Confluence** to manage **5G infrastructure upgrade requirements**.

### 4. Assess Impact on Architecture
- **What:** Analyze how **new requirements affect existing architecture components**.
- **Example:** A **retail chain** evaluates the impact of **omnichannel shopping experiences** on its **current e-commerce and inventory systems**.

### 5. Ensure Traceability Across ADM Phases
- **What:** Link requirements to **business goals, architecture artifacts, and implementation projects**.
- **Example:** A **manufacturing firm** ensures that **IoT-driven predictive maintenance** aligns with **enterprise data strategy and cloud adoption roadmap**.

### 6. Handle Requirement Changes
- **What:** Implement a **change management process** to review, approve, and integrate modifications.
- **Example:** A **government agency** updates its **national identity verification system** to comply with **new data privacy laws**.

### 7. Feed Changes Back into ADM Cycle
- **What:** Continuously **refine and integrate evolving requirements** into architecture.
- **Example:** A **fintech startup** revises its **AI-based credit risk assessment models** based on **new regulatory guidance from financial authorities**.

---

## Inputs

| Input | Description | Example |
|---|---|---|
| **Business Strategy & Objectives** | Defines high-level goals and strategic priorities. | A **cloud services provider** prioritizing **cost-optimized multi-cloud strategies**. |
| **Stakeholder Requirements** | Functional and non-functional needs from business and IT. | A **pharmaceutical company** requiring **AI-based drug discovery tools**. |
| **Compliance & Regulatory Standards** | Defines legal and industry-mandated requirements. | A **healthcare network** ensuring **GDPR-compliant patient data processing**. |
| **Enterprise Policies & Guidelines** | Internal frameworks governing IT and business operations. | A **banking firm** enforcing **risk management policies in IT projects**. |
| **Previous ADM Iterations** | Architecture components and decisions from past ADM cycles. | A **retail chain** reviewing **legacy POS system dependencies before migration**. |

---

## Outputs

| Output | Description | Example |
|---|---|---|
| **Requirements Repository** | A centralized system for capturing and tracking requirements. | A **telecom company** storing **5G deployment requirements in ServiceNow**. |
| **Traceability Matrices** | Maps requirements to business goals and architecture artifacts. | A **logistics company** mapping **fleet tracking system enhancements** to **supply chain KPIs**. |
| **Impact Assessment Reports** | Evaluates how new requirements affect architecture components. | A **government cybersecurity agency** assessing **zero-trust security adoption impact**. |
| **Updated Architecture Roadmap** | Aligns new requirements with implementation priorities. | A **global retailer** integrating **AI-driven customer insights** into **next-year IT strategy**. |
| **Change Request Log** | Tracks modifications and approvals to ensure governance. | A **financial institution** managing **blockchain transaction security updates**. |

---

## Popular Tools for Requirements Management

| Tool | Description | Use Case |
|---|---|---|
| **Jira** | Agile project management and requirements tracking. | **Managing iterative changes in cloud migration projects**. |
| **IBM DOORS** | Enterprise requirements management. | **Tracking compliance for aerospace and defense architectures**. |
| **ServiceNow ITBM** | IT business management and change tracking. | **Aligning IT projects with enterprise architecture objectives**. |
| **Confluence** | Centralized documentation and collaboration. | **Storing and versioning architecture-related requirements**. |
| **Azure DevOps** | DevOps lifecycle management and backlog tracking. | **Managing infrastructure modernization requirements**. |

---

## Summary

The **Requirements Management phase** ensures that **business needs, IT capabilities, and regulatory changes** are **continuously tracked, validated, and integrated** into the architecture lifecycle. By maintaining a **structured, traceable, and iterative process**, organizations can **adapt to change while maintaining architectural integrity**.
# Requirements Management

## **Objective**
Requirements Management in TOGAF ensures that **architecture development aligns with business needs** and remains adaptable to changes. It acts as a **continuous process** that integrates with all ADM phases to track, prioritize, and validate evolving requirements.

### **Key Goals:**
- Establish **traceability** between business objectives and architectural decisions.
- Maintain **consistency and accuracy** in requirements across all ADM phases.
- Adapt to **changing business needs** through effective requirement updates.
- Ensure **stakeholder alignment** to prevent project scope creep.

---

## **Inputs**
Requirements Management relies on multiple inputs from various ADM phases:

| **Input** | **Description** | **Example** |
|-----------|---------------|-------------|
| **Business Goals & Strategies** | High-level business objectives that the architecture must support. | *A retail company wants to unify its online and in-store experiences.* |
| **Stakeholder Needs** | Concerns and requirements gathered from key stakeholders. | *The CFO requires real-time financial reporting, while IT wants cloud compatibility.* |
| **Architecture Vision (Phase A)** | High-level aspirational view of the architecture’s capabilities. | *A logistics company aims to implement AI-driven route optimization.* |
| **Gap Analysis (Phases B, C, D)** | Identified deficiencies between current and target architectures. | *An outdated ERP system lacks API integrations for modern apps.* |
| **Regulatory & Compliance Standards** | Legal and industry requirements that the architecture must adhere to. | *GDPR for data privacy, PCI-DSS for payment security.* |
| **Technology Constraints** | Limitations due to existing IT infrastructure, budgets, or skills. | *A legacy mainframe system prevents seamless cloud adoption.* |

---

## **Steps in Requirements Management**
The Requirements Management process follows these steps to **ensure controlled handling of evolving requirements**:

### **1. Capture Requirements**
- Conduct **workshops, surveys, and stakeholder interviews**.
- Document both **functional and non-functional requirements**.
- Example: *A hospital IT system must ensure patient data security (non-functional) and support digital appointment booking (functional).*

### **2. Validate & Prioritize Requirements**
- Check for **alignment with business strategy** and feasibility.
- Categorize requirements based on priority: **Must-Have, Should-Have, Nice-to-Have**.
- Example: *A bank must meet regulatory compliance before implementing AI-based customer insights.*

### **3. Integrate with ADM Phases**
- Requirements flow **bi-directionally** between ADM phases.
- Ensure architecture decisions remain aligned with updated business needs.
- Example: *A retail company pivots to mobile-first development after customer trends shift.*

### **4. Assess Impact of Changes**
- Evaluate if requirement changes affect other areas of architecture.
- Adjust roadmaps, budgets, and technical dependencies as needed.
- Example: *A new cybersecurity requirement necessitates reworking the cloud migration plan.*

### **5. Track & Maintain Requirements**
- Maintain a **Requirements Repository** to track status and history.
- Use tools like **JIRA, Confluence, or IBM DOORS** for traceability.
- Example: *A government agency tracks evolving legislative IT mandates.*

---

## **Outputs**
Effective Requirements Management produces valuable outputs:

| **Output** | **Description** | **Example** |
|-----------|---------------|-------------|
| **Requirements Repository** | Centralized database tracking requirement changes over time. | *A retail chain logs all e-commerce system enhancements.* |
| **Requirements Impact Assessment** | Document evaluating how changes affect the architecture. | *A cloud-first strategy disrupts legacy app compatibility.* |
| **Updated Architecture Deliverables** | Adjusted architecture documents reflecting new requirements. | *A bank updates its IT roadmap to include blockchain integration.* |
| **Stakeholder Approval Reports** | Signed-off documents confirming alignment with business goals. | *An executive board approves CRM upgrades for customer retention.* |

---

## **Real-World Use Case: Requirements Management in Action**

### **Scenario: Implementing a Unified E-Commerce & In-Store Experience**
A multinational **retail company** wants to provide a **seamless shopping experience** by integrating its **brick-and-mortar stores with its online platform**.

### **Steps Followed:**
1. **Capture Requirements**:
   - Customers demand **buy-online-pickup-in-store (BOPIS)** functionality.
   - Business owners want **real-time inventory updates across locations**.
   
2. **Validate & Prioritize**:
   - Regulatory compliance for **secure online transactions** is mandatory.
   - AI-powered **personalized product recommendations** are a future goal.
   
3. **Integrate with ADM**:
   - Phase A defines **architecture vision** for omnichannel retail.
   - Phase B identifies **process changes** to unify supply chain data.
   - Phase C designs **application and data architectures** for e-commerce and in-store POS.
   
4. **Assess Impact**:
   - Moving to **cloud-based inventory management** requires refactoring legacy systems.
   - Security teams evaluate new **fraud detection mechanisms**.
   
5. **Track & Maintain**:
   - JIRA tracks requirement changes during iterative implementation.
   - Stakeholders review impact assessments before full-scale rollout.
   
### **Outcome:**
- **Real-time inventory synchronization** improves stock availability.
- **Frictionless customer experience** leads to **higher sales conversion**.
- **Regulatory compliance** ensures secure payments and data protection.

---

## **Key Takeaways**
- **Requirements Management ensures architecture evolution aligns with business needs.**
- **Real-world constraints like compliance, technology limits, and stakeholder input shape requirements.**
- **A structured process enables organizations to adapt to changes while maintaining alignment with TOGAF principles.**
