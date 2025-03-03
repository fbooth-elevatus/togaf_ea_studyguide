# Preliminary Phase: Framework and Principles

## Purpose
Prepare the organization for EA work by defining the framework, principles, and tools to guide the architecture development process.

- **Key Objective:** Set the foundation for a successful ADM cycle by establishing the "how" of enterprise architecture.

## Key Activities
- **Define the EA Team and Organization:**
  - Establish the structure and roles for the enterprise architecture effort. This includes identifying key personnel, their responsibilities, and how they collaborate across the organization.
  - **Detail:** Determine who leads the EA initiative (e.g., Chief Architect), who contributes domain expertise (e.g., business analysts, IT specialists), and how they report (e.g., to a steering committee or CIO). Clarify team size, skills, and whether external consultants are needed.
  - **Example:** For a retail company, the EA team might include:
    - **Chief Architect:** Oversees the EA strategy and ADM process.
    - **Business Architect:** Maps business processes (e.g., order fulfillment).
    - **IT Specialist:** Assesses current technology stack.
    - **Project Manager:** Coordinates timelines and deliverables.
    - **Organization:** Reports to a governance board with the CIO and VP of Operations, meeting bi-weekly to align EA with business goals.

- **Select and Tailor the Architecture Framework (e.g., TOGAF):**
  - Choose an EA framework and adapt it to the organization’s specific needs, size, and industry.
  - **Detail:** Review frameworks like TOGAF, Zachman, or FEAF, then customize TOGAF’s ADM phases, deliverables, or techniques to fit the enterprise’s complexity, culture, or existing practices.
  - **Example of Tailoring TOGAF:** A small retail startup tailoring TOGAF might:
    - Simplify Phase C by focusing only on Application Architecture (skipping detailed Data Architecture due to limited systems).
    - Shorten Phase F (Migration Planning) to a single sprint, given a lean IT setup.
    - Use lightweight tools (e.g., spreadsheets vs. enterprise modeling software) to match resource constraints.
    - Result: A streamlined TOGAF ADM tailored for agility and minimal overhead.

- **Define Architecture Principles:**
  - Establish high-level guidelines that shape architecture decisions and ensure consistency across the EA effort.
  - **What is a Principle?** A principle is a qualitative statement of intent or a rule that guides design and decision-making. It’s broad, enduring, and reflects organizational values or goals—unlike specific standards or policies.
  - **Detail:** Principles are derived from business strategy, stakeholder input, and industry best practices. They’re documented with a name, statement, rationale, and implications.
  - **Examples of Existing Principles:**
    - **Principle: Business Continuity**
      - **Statement:** Systems must ensure uninterrupted business operations.
      - **Rationale:** Downtime costs revenue and customer trust.
      - **Implication:** Architectures prioritize redundancy (e.g., backup servers).
    - **Principle: Data is an Asset**
      - **Statement:** Data must be accurate, accessible, and secure.
      - **Rationale:** Reliable data drives decisions and competitiveness.
      - **Implication:** Invest in data governance and master data management.
    - **Principle: Technology Independence**
      - **Statement:** Solutions favor vendor-neutral standards.
      - **Rationale:** Avoids lock-in and enhances flexibility.
      - **Implication:** Use open APIs over proprietary systems.

- **Identify Tools and Governance Structures:**
  - Select tools for modeling, documenting, and managing the architecture, and define governance to oversee the EA process.
  - **Detail:** Tools support the ADM (e.g., diagramming, repositories), while governance structures (e.g., boards, policies) ensure alignment and accountability.
  - **Examples:**
    - **Tools:**
      - **ArchiMate:** For modeling architecture layers (free with Archi tool).
      - **Enterprise Architect:** Comprehensive EA tool for diagrams and traceability.
      - **Jira:** Tracks EA tasks and work packages.
      - **Google Drive:** Simple storage for shared docs and templates.
    - **Governance Structures:**
      - **Architecture Board:** Senior leaders (e.g., CIO, CTO) meet monthly to approve deliverables and resolve disputes.
      - **Compliance Checklist:** Ensures each phase meets principles (e.g., “Does Phase D support data security?”).
      - **Change Control Process:** Manages updates to the architecture post-Phase H via a formal request system.

## Inputs
- **Organizational Context:** Business goals, structure, and culture.
- **Existing Frameworks:** Current EA practices or standards in use.

## Outputs
- **Architecture Principles:** Documented guidelines (e.g., “Data is an Asset”).
- **Tailored Architecture Framework:** Customized TOGAF ADM for the organization.
- **Governance Structure:** Defined team roles and oversight mechanisms.
- **Toolset:** Selected tools ready for EA work.

## Study Notes
- **Exam Focus:** How does this phase set the tone for the ADM cycle? Know the outputs (principles, framework) and their purpose.
- **Key Concept:** Principles guide all subsequent phases—understand their role as “guardrails.”
- **Tailoring:** Be ready to explain why and how TOGAF is adapted (e.g., for small vs. large orgs).