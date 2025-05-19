# <span style="color:#198110">Request for Proposal to Qubic regarding TxGuard</span>

> by DataLedgerLabs (Smashing Blocks)

## Table of Contents

- [Executive Summary](#executive-summary)
- [I. Pain Point Addressed](#i-pain-point-addressed)
- [II. Value Proposition and Differentiation](#ii-value-proposition-and-differentiation)
- [III. Project Overview](#iii-project-overview)
- [IV. Global Functionality and Building Strategy](#iv-global-functionality-and-building-strategy)
- [V. Inputs and Outputs](#v-inputs-and-outputs)
- [VI. Requirements](#vi-requirements)
- [VII. Architecture](#vii-architecture)
- [VIII. Metrics and KPIs](#viii-metrics-and-kpis)
- [IX. Business Model](#ix-business-model)
- [X. Risk Considerations](#x-risk-considerations)
- [XI. Competitors](#xi-competitors)
- [XII. Stakeholder Alignment](#xii-stakeholder-alignment)
- [XIII. Marketing and Communication Strategy](#xiii-marketing-and-communication-strategy)
- [XIV. The Team](#xiv-the-team)
- [XV. Budget Estimation](#xv-budget-estimation)
- [XVI. Milestones and Estimated Timeline](#xvi-milestones-and-estimated-timeline)
- [XVII. Use Cases](#xvii-use-cases)
- [XVIII. Annex: Phase 2 Planning – Predictive Capabilities and Compliance](#xviii-annex-phase-2-planning--predictive-capabilities-and-compliance)

---

# <span style="color:#198110">Executive Summary</span>

The financial landscape has evolved clients now use blockchain addresses as identities alongside traditional accounts, engaging in decentralized activities that challenge conventional oversight. Can financial entities truly understand these behaviors while adhering to Anti-Money Laundering (AML) and Know Your Transfer (KYT) standards? **DataLedgerLabs** presents **TxGuard**, a comprehensive **"Business-to-Artificial Intelligence"** (B2AI) solution designed for traditional and non-traditional financial entities. The solution is planned to be built on Amazon Web Services (AWS). **TxGuard** delivers a comprehensive view of financial identities on the **Qubic blockchain**, ensuring compliance with AML and KYT requirements.

TxGuard is structured as a two-phase deployment strategy that maximizes scalability, reduces risk, and ensures rapid value delivery:

- Phase 1 - Incubation: This phase, which is the focus of the present RFP, concentrates on data extraction, semantic curation, descriptive analytics, and natural language exposure of Qubic’s tick-level data. It is designed to provide immediate data value and enable intuitive interaction with blockchain datasets via natural language queries, without requiring a user-facing UI.

- Phase 2 - Acceleration: Planned for future execution, this phase will integrate advanced predictive analytics, anomaly detection, and behavioral insights. It aims to elevate compliance efforts and decision-making through machine learning capabilities. A preliminary outline of Phase 2 is included in the annex.

The total implementation time for Phase 1 is estimated approximately in one year, with a staffing level of approximately 1.2 Full-Time Equivalents (FTE). Budget planning for this phase follows the P10 (best case) scenario. Full cost and time allocations are detailed in the XVI. [Milestones and Estimated Timeline](#xvi-milestones-and-estimated-timeline)

<br>

# <span style="color:#198110">I. Pain Point Addressed</span>

The rules have changed: clients are no longer defined solely by bank accounts; they now possess blockchain identities that reflect their decentralized financial activities. Financial institutions face a critical challenge in adapting their tools and processes to understand these new identities while maintaining compliance with AML and KYT regulations. This is where TxGuard steps in to support the transition by:

- Providing a comprehensive view of **financial behavior on the Qubic blockchain**.
- Transforming complex, anonymous data into clear, **actionable insights**.
- **Enabling secure, data-driven decisions** for fraud prevention, compliance, and market intelligence.
- **Connecting on-chain activity with off-chain compliance frameworks**. It empowers centralized and decentralized exchanges, as well as traditional financial institutions, to track, analyze, and respond to blockchain-based financial behavior, ensuring regulatory compliance.

By bridging traditional finance with blockchain ecosystems, **TxGuard** ensures financial institutions can confidently navigate this emerging landscape while aligning with global compliance standards.

<br>

# <span style="color:#198110">II. Value Proposition and Differentiation</span>

**TxGuard** stands out by combining automation, advanced analytics, and user-centric design to deliver unmatched value in the current market:

- **Automation**: Automated data ingestion and transformation pipelines using AWS tools reduce manual effort, ensuring efficiency and scalability.

- **Cost-Performance Harmony**: Tiered pricing models (Basic, Optimal, Comprehensive) balance technical capability with affordability, making the solution accessible.

- **Natural Language Interface**: An intuitive natural language consultation feature allows users (IAs, entities, or Qubic blockchain partners) to query complex blockchain data without specialized technical knowledge, enhancing accessibility and decision-making.

- **Secure Cloud Infrastructure**: Built on AWS, the solution offers enterprise-grade security, scalability, and reliability for handling sensitive financial data and high-volume blockchain analytics ([AWS Web3 Blog, 2024](https://aws.amazon.com/blogs/web3/)).

- **Descriptive Analytics Foundation**: The Dapp provides robust descriptive key variables and insights into transaction patterns and customer behaviour.

- **Customizable Insights**: The user can parameterize the variables they desire to extract so they can meet their specific needs.

- **Enhanced Regulatory Compliance**: **_Phase 2_** builds on this with near real-time insights by leveraging curated blockchain data for AML and KYT compliance. This proactive approach helps financial entities stay ahead of regulatory demands and positions them for effective risk management and fraud detection in non-traditional assets inspired by [Chainalysis KYT, 2025](https://www.chainalysis.com/product/kyt/).

<span style="color:#124C89">**Our Value Proposition**</span>

**TxGuard** empowers Qubic's owner identities and financial entities with blockchain intelligence, addressing fraud prevention and market insight needs in a growing analytics market valued at USD 2.89 billion in 2025, within a global blockchain market projected at USD 57.72 billion ([Grand View Research, 2024](https://www.grandviewresearch.com/industry-analysis/blockchain-technology-market)).

Leveraging Qubic, which processes up to 55 million transactions per second (The Qubic Team, 2024), TxGuard positions itself as a first-mover in an underserved ecosystem. The platform offers a strategic advantage with the scalability to extend across wider blockchain networks (101blockchains.com, 2025).

The potential impact of this solution is substantial, presenting a unique opportunity to lead the next generation of blockchain compliance and intelligence.

<br>

# <span style="color:#198110">III. Project Overview</span>

**TxGuard** is a Business-to-Artificial Intelligence (B2AI) Agent that enables natural language queries to deliver actionable descriptive analytics from Qubic tick data, including transaction patterns, identity behaviors, and risk factors. Aligned with the **BUIDL** philosophy, TxGuard drives active engagement with blockchain technology by empowering users to harness data effectively. It strengthens regulatory compliance, enhances decision-making, and lays the foundation for predictive analytics.

- **Phase 1 (Incubation)**: Establish a robust pipeline for tick data extraction, curation, and descriptive analytics with natural language access.

- **Phase 2 (Acceleration)**: Add predictive models for anomaly detection and trend forecasting, amplifying AML/KYT capabilities.

- **Target Users**: Qubic´s owner identity, financial entities, compliance officers, risk managers, and investment strategists seeking actionable blockchain insights.

## <span style="color:#124C89">1. Scope Phase 1</span>

- **Tick Data Extraction & Curation**: Extract Qubic tick data (e.g., transaction logs) and curate it for accuracy and relevance.

- **Natural Language Interface**: Enable intuitive querying of tick data in plain language (English).

- **Descriptive Analytics Engine**: Compute metrics like transaction volume and frequency for **_Phase 1_** insights.

- **AWS Cloud Infrastructure**: Host a secure, scalable Dapp environment on AWS.

- **Integration Capabilities**: Provide a system for syncing with existing systems.

- **Documentation & Training**: Supply comprehensive user guides and training sessions.

<br>

## <span style="color:#124C89">2. Out of Scope</span>

- Development of predictive analytics models (reserved for Phase 2)
- Integration and services for specific third-party financial entities.
- Query languages beyond English.
- Include the 100% of Qubic's ticks information.

<br>

# <span style="color:#198110">IV. Global Functionality and Building Strategy</span>

As previously mentioned, TxGuard’s development is strategically divided into two phases to ensure a structured, efficient, and risk-mitigated approach. The high-level functionality of Phase 1 is outlined below:

## <span style="color:#124C89">Phase 1: Incubation (8–12 Months)</span>

**TxGuard’s Phase 1 (Incubation)** functionality is structured around four core components including **Collection**, **Curation**, **Descriptive Analytics Engine**, and **Exposure**. These modules are designed to establish a strong foundation for Qubic tick data processing and analytics, enabling financial institutions to derive actionable insights for compliance, fraud detection, and market intelligence.

- **Collection**  
  Ingests raw Qubic tick data, including transaction logs, tick headers, and metadata—via a Qubic Archive, and stores it for processing.
- **Data Curation**  
  Cleans, enriches, and unifies incoming tick data formats. Applies semantic enhancements to support advanced querying and pattern recognition.
- **Descriptive Analytics Engine**  
  Processes curated data to generate key metrics and behavioral patterns relevant to use cases such as transaction monitoring, risk analysis, and customer profiling.
- **Exposure**  
  Develops and configures MCPs (Model Context Protocol) and intelligent agents capable of interpreting and responding to user queries in natural language. Rather than building a traditional user-facing frontend, the system will leverage the interface of the integrated Large Language Model (LLM) to enable direct querying of the platform’s database. This approach provides immediate utility while keeping the focus on core intelligence and data capabilities.

These components work cohesively to deliver reliable, explainable, and structured financial intelligence from decentralized blockchain data.

<br>

![Phase1](https://github.com/user-attachments/assets/f7f7d7eb-afed-4df9-bd28-5c86e87e2e71)

<br>

> **Out of Scope**:  
> Full UI/UX design, external security audits, and third-party platform integrations.
> As outlined in previous sections, **predictive modelling, risk scoring, and advanced user role functionalities are planned for Phase 2**.

The diagram below illustrates a simplified schematic of the overall process:

<br>

![OverviewTxGuard](https://github.com/user-attachments/assets/aae1f372-ead1-4fa8-afd9-a3d338b3f8a7)

# <span style="color:#198110">V. Inputs and Outputs</span>

**TxGuard’s** ability to deliver actionable insights relies on a clearly defined flow of inputs and outputs that processes Qubic’s tick-based blockchain data and translates it into usable intelligence. The following outlines the key data inputs and resulting outputs across both deployment phases.

## <span style="color:#124C89">1. Inputs</span>

### **Phase 1: Descriptive Analytics**

- **Tick Data**: Qubic transaction logs, tick headers, and metadata
- **User Queries**: Natural language prompts and structured search inputs
- **Configuration Parameters**:
  - Transaction history range
  - Preferred output formats
  - Security guardrails and filters

## <span style="color:#124C89">2. Outputs</span>

### **Phase 1: Descriptive Results**

- **Transaction Insights**: Summaries and key metrics (e.g., transaction volume, frequency, address activity)
- **Query Responses**: Structured results (e.g., tabular, JSON) aligned with user prompts
- **Audit Logs**: Logs capturing user activity and access for traceability

<br>

# <span style="color:#198110">VI. Requirements</span>

**TxGuard’s** functional and non-functional requirements define the core capabilities to process and analyze Qubic tick data while ensuring AML/KYT compliance. These specifications enable scalable, secure, and user-accessible blockchain intelligence for financial institutions. Requirements are categorized by functionality, performance, usability, and compliance coverage across both deployment phases.

> **Disclaimer:** Not all components of the proposed architecture will be used in the final implementation. Depending on technical and operational constraints, alternatives may be considered.

## <span style="color:#124C89">1. Functional Requirements</span>

- **FR1**: Ingest Qubic tick data with near real-time synchronization; validate and preprocess for integrity
- **FR2**: Curate and transform tick data for efficient querying and pattern recognition (e.g., transaction bursts, inactivity)
- **FR3**: Enable retrieval of historical transaction data over user-defined timeframes and between Qubic identities
- **FR4**: Implement data analytics and a natural language query interface (English support)
- **FR5**: Output structured query responses (e.g., JSON, tables)

## <span style="color:#124C89">2. Non-Functional Requirements</span>

- **NFR1**: Support >100 concurrent users; return 75% of query responses in under 10 seconds
- **NFR2**: Ensure data integrity via validation, duplication checks, and error handling
- **NFR3**: Modular system architecture with comprehensive documentation and CI/CD readiness

<br>

# <span style="color:#198110">VII. Architecture</span>

The data pipeline architecture for **TxGuard** is designed with modularity, fault tolerance, and scalability in mind, leveraging AWS services within a European Virtual Private Cloud (VPC) framework. It separates responsibilities across collection, curation, analytics, and storage to ensure efficient and secure data handling.

> Disclaimer: This architecture is subject to iterative refinement during development to better align with TxGuard’s design goals and stakeholder feedback, ensuring optimal performance, compliance, and usability for financial entities.

## <span style="color:#124C89">Core Architectural Layers</span>

- **Collection Layer**  
   A microservice (Node.js-based) fetches raw tick data from the Qubic network and routes it into the curation pipeline for further processing.
- **Curation & Analytics Layer**  
   The curation service transforms raw tick data into structured, semantically tagged formats. Results are stored in a PostgreSQL database to support query performance and analytics processing.
- **Data Persistence Layer**
  - **DynamoDB** is used for fast-access key-value mappings and operational data.
  - **PostgreSQL** stores relational data, powering historical insights and integration with AI agents via MCP.
  - **Amazon S3** provides long-term storage of legacy and batch-processed datasets cost-efficiently.
- **Resilience and Backup**
  - PostgreSQL and DynamoDB are backed up via native AWS mechanisms
  - EC2 services are distributed across multiple Availability Zones (Multi-AZ) for high availability

## <span style="color:#124C89">Cloud-Native Capabilities</span>

This architecture supports:

- Horizontal scalability for concurrent data processing
- Real-time querying through PostgreSQL with AI/NLP interfaces
- Compatibility with the [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)

### <span style="color:#124C89">Illustrative Diagram</span>

![architecture](https://github.com/user-attachments/assets/2848fdac-2be4-4c66-9771-02ff0f0cc785)

<br>

# <span style="color:#198110">VIII. Metrics and KPIs</span>

**TxGuard’s** performance and business success will be continuously evaluated using a defined set of metrics and key performance indicators (KPIs). These span system responsiveness, user satisfaction, compliance impact, and predictive capability, ensuring both technical rigor and organizational alignment across **Phase 1** and **Phase 2**.

### <span style="color:#124C89">1. System Performance Metrics</span>

- **Data Processing Speed**: Average processing time for new Qubic tick transactions
  - _Target_: < 10 seconds for 90% of transactions
- **Data Accuracy**: Percentage of tick data accurately ingested and processed
  - _Target_: ≥ 99.999%

### <span style="color:#124C89">2. User Adoption and Satisfaction Metrics</span>

- **User Satisfaction Score**: Overall satisfaction on a 1–10 scale
  - _Target_: ≥ 7.5
- **Feature Utilization Rate**: Percentage of features used monthly
  - _Target_: ≥ 70% of features used at least once per month

<br>

# <span style="color:#198110">IX. Business Model</span>

TxGuard’s performance and business success will be measured through a defined set of metrics and key performance indicators (KPIs), including system responsiveness, user satisfaction, compliance impact, and predictive capabilities. These metrics ensure both technical rigor and strategic alignment across the development roadmap, spanning Phase 1 and the more commercially oriented Phase 2.

As this RFP pertains exclusively to Phase 1, the platform will not include a user-facing UX/UI layer. Instead, interaction will be facilitated via a natural language interface powered by a Large Language Model (LLM), enabling database queries without a traditional frontend.

Formal subscription tiers will be introduced in Phase 2, where a fully featured product, starting with a beta version of the Basic Tier, will be released to early users for testing and feedback.

### <span style="color:#124C89">Subscription Tiers</span>

- **Basic Tier**
  - Access to core descriptive analytics
  - Limited query capabilities
- **Optimal Tier**
  - Full access to all **Phase 1** features
  - Natural language querying extended
- **Comprehensive Tier**
  - Includes **Phase 2** capabilities
  - Predictive analytics and full AML/KYT compliance support

> **Disclaimer**: Final pricing and packaging are subject to a full market study prior to product launch.

<br>

# <span style="color:#198110">X. Risk Considerations</span>

The successful deployment of TxGuard, especially during Phase 1, relies on the proactive identification and mitigation of technical, operational, and regulatory risks. Below is a comprehensive risk mitigation strategy that aligns with AWS best practices and ensures the resilience of the blockchain infrastructure.

### <span style="color:#124C89">Backup, Recovery, and Disaster Recovery</span>

- **Backup Strategy**  
  Daily snapshots with versioning to prevent accidental data loss.
- **Recovery Plan**  
  Analytics pipelines backed up regularly via AWS Backup, enabling rapid re-deployment in the event of corruption or system failure.
- **Disaster Recovery**  
  All services deployed across multiple AWS Availability Zones (Multi-AZ) to ensure resilience and high availability.

### <span style="color:#124C89">Development Quality and Maintainability</span>

- **Codebase Consistency**  
  Structured peer review at every milestone, enforced through CI pipelines and GitHub Actions.
- **Documentation Management**  
   Dedicated documentation cycles will be established for each phase to avoid knowledge silos and maintain technical transparency.

### <span style="color:#124C89">Regulatory and Compliance Risks</span>

- **Auditability Gaps**  
  All user access logs and decision points will be stored immutably using AWS CloudTrail, which supports both external and internal audits.

### <span style="color:#124C89">Human Resource and Continuity Risks</span>

- **Key Personnel Availability**  
  This risk will be mitigated by cross-training, conducting knowledge-sharing sessions, and implementing rotational code ownership to distribute expertise and reduce single points of failure.

<br>

# <span style="color:#198110">XI. Competitors</span>

The blockchain analytics landscape is competitive, with several established players offering AML/KYT services. However, **TxGuard** differentiates itself by targeting an underserved segment, **the Qubic ecosystem**, while focusing on accessibility, flexibility, and cost-efficiency. Potential competitors could be considered on most of the data intelligence platforms already in the market such as [chainalysis](https://www.chainalysis.com/chainalysis-kyt-certification/), [ciphertrace](https://www.mastercard.com/global/en/business/issuers/crypto.html), [pixelplex](https://pixelplex.io/know-your-transaction/)

### <span style="color:#124C89">Key Differentiators</span>

- **User-Centric Design**  
  Unlike competitors that require extensive technical knowledge, **TxGuard** features a natural language interface, empowering non-technical users such as compliance officers and financial advisors to interact with complex blockchain data effortlessly.
- **Qubic Ecosystem Focus**  
  **TxGuard** provides a first-mover advantage in the Qubic ecosystem, a rapidly evolving but currently under-analyzed blockchain platform capable of processing over 55 million smart contract executions per second.
- **Cost Efficiency**  
  While platforms like Chainalysis offer potent features, their enterprise pricing may be out of reach for smaller institutions.

<br>

# <span style="color:#198110">XII. Stakeholder Alignment</span>

The success of **TxGuard** relies on strategic alignment among a diverse set of stakeholders. Each group plays a vital role in shaping the platform’s direction, ensuring it meets the technical, compliance, and usability expectations of financial institutions navigating Qubic’s decentralized and tick-based ecosystem.

### <span style="color:#124C89">External Stakeholders</span>

- **Regulatory Bodies**

  - **Impact**: May audit TxGuard to verify alignment with evolving regulatory expectations for blockchain activity monitoring.

- **Qubic´s Identify Owners and Financial Entities (traditional and no-traditional)**

  - **Impact**: Gain insights that enhance service offerings, such as lending, while benefiting from transparency and privacy compliance.

- **Technology Partners (e.g., Qubic Network)**

  - **Impact**: Support TxGuard’s performance, scalability, and near real-time synchronization.

- **Advisory Partners (e.g., Blockchain Engineers, Compliance Experts, Cybersecurity Consultants)**
  - **Impact**: Enhance trust, compliance coverage, and system resilience.

### <span style="color:#124C89">Project Team Stakeholders</span>

- **Project Team**:
  - **Roles**:
    - **Project Manager**: Oversees delivery timelines and scope.
    - **Business Analysts**: Define user needs and regulatory requirements.
    - **Software Developers**: Build and maintain core system components.
    - **Data Scientists**: Engineer insights and models for AML/KYT analytics.
    - **UX/UI Designers**: Ensure intuitive user interfaces are aligned with accessibility standards.
    - **QA Testers**: Maintain system reliability through rigorous testing.
    - **Technical Writers**: Deliver end-user documentation and training materials.
  - **Impact**: Execute TxGuard’s roadmap by combining technical excellence with compliance-driven architecture.

<br>

# <span style="color:#198110">XIII. Marketing and Communication Strategy</span>

A clear and compelling marketing and communication strategy is essential to driving awareness, adoption, and credibility for TxGuard within the blockchain and financial compliance sectors. This strategy focuses on reaching stakeholders with tailored messaging across high-impact channels.

### <span style="color:#124C89">Target Audience</span>

- Traditional and non-traditional financial entities
- Qubic identity owners
- Blockchain-focused investment firms and advisory groups

### <span style="color:#124C89">Channels</span>

- **Qubic Ecosystem Channels**: Leverage Qubic’s grants program and technical blog ecosystem for visibility and integration.
- **LinkedIn**: Thought leadership and updates tailored to compliance professionals and fintech executives.
- **Medium**: Technical articles on natural language processing for blockchain queries, use case spotlights, and system performance insights.
- **Conferences**: Participate in blockchain compliance and Web3 developer events to showcase TxGuard’s capabilities.

<br>

# <span style="color:#198110">XIV. The Team</span>

**TxGuard** is built by a multidisciplinary team with deep expertise in blockchain engineering, data science, backend infrastructure, and regulatory technology. The team operates within a **horizontal structure** to promote agility, shared ownership, and innovation, ensuring the successful delivery of a scalable, secure, and regulation-ready analytics platform.

### <span style="color:#124C89">[Andrés León](https://www.linkedin.com/in/andres-leon-bohorquez/) – Senior Backend Architect and Blockchain Educator</span>

With over 20 years of experience in backend systems and distributed architectures, Andrés began coding in BASIC at age 11. He discovered cryptographic systems and digital payments in 2005 through RipplePay at the Polytechnic University, which sparked his commitment to decentralized infrastructure. A professor at CodeCrypto Academy, Andrés is a cornerstone in TxGuard’s architecture, designing scalable systems for tick data ingestion and processing.
**Expertise**: Databases, backend performance, secure systems, distributed ledgers.

### <span style="color:#124C89">[Jacky Barraza](https://www.linkedin.com/in/jackybarraza/) – Senior Data Scientist</span>

Jacky brings 18+ years of experience in AI and cloud-native data engineering. She holds a Master’s in Blockchain Engineering from CodeCrypto Academy and has led predictive analytics projects across finance, energy, and digital identity. Her leadership on **Bloodchain**, a privacy-preserving blockchain system, reflects her commitment to secure, explainable AI. In TxGuard, she drives anomaly detection, compliance scoring, and data modelling.
**Expertise**: Machine learning, Azure ML, decentralized architectures, analytics pipelines.

### <span style="color:#124C89">[Jose Fco Gámez](https://www.linkedin.com/in/dalzemag/) – Senior Solution Architect</span>

Jose has over 15 years of experience across IoT, backend platforms, CTO and DevOps. A Master’s student in Blockchain Engineering, he specializes in cloud-native architecture and CI/CD workflows. His experience spans Shopify, MongoDB, and secure API design. At TxGuard, Jose ensures infrastructure resilience and service modularity.
**Expertise**: AWS, DevOps pipelines, secure APIs, MQTT/Node-RED integration.

### <span style="color:#124C89">[Javier Ruiz-Canela López](https://www.linkedin.com/in/javier-ruiz-canela-lopez-a293a1a3/) – Senior Software Engineer</span>

Javier brings a decade of experience in regulated sectors such as finance and pharmaceuticals. As a Master’s student in Blockchain Engineering, he applies his knowledge of Java, Spring, and secure identity systems (Keycloak, LDAP) to ensure TxGuard’s IAM and analytics services are enterprise-grade.
**Expertise**: Microservices, IAM systems, event-driven architecture, Spring Boot, Kafka.

<br>

# <span style="color:#198110">XV. Budget Estimation</span>

This section outlines a high-level breakdown of the estimated effort and associated costs required to implement Phase 1. The estimates cover the this RFP report and all major functional stages—Collection, Curation, Descriptive Analytics, and Exposure—and include infrastructure setup, core development, deployment, documentation, and testing activities.

The project planning and timelines are presented using the P50 (baseline) scenario, which reflects a realistic balance between best case and conservative assumptions regarding development velocity and resource availability. The P10 scenario represents a more conservative approach, which will be the selected budget on this RFP.

This approach allows the team to demonstrate feasibility within a lean resource model while maintaining flexibility to scale if necessary. Presenting the budget through the P10 lens ensures financial efficiency for early-stage planning and facilitates quicker approval by minimizing initial funding requirements, without compromising the integrity of the technical roadmap.

### <span style="color:#124C89">Development Effort by Phase and Task</span>

<br>

| **Phase / Task**                                                       | Subtasks                                                                      | Estimated Time (weeks) |
| ---------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ---------------------- |
| <span style="color:#124C89">**0. RFP Preparation**</span>              |                                                                               | **1 week**             |
| - Documentation & Planning                                             | • Build the RFP draft for Qubic <br>• Project scoping                         | 1 week                 |
| - Repository & Project Setup                                           | • Create base repo <br>• Dev environment bootstrap                            | Included above         |
| <span style="color:#124C89">**1. Collection**</span>                   |                                                                               | **11 weeks**           |
| - Prospection                                                          | • Node access validation <br>• Tick log inspection <br>• Data sync validation | 1 week                 |
| - Development                                                          | • Service development (Node.js)                                               | 2 weeks                |
| - Architecture Setup                                                   | • VM/containers <br>• Network config <br>• Load balancing                     | 1 weeks                |
| - Deployment                                                           | • Implementation <br>• Resilience <br>• Testing                               | 2 weeks                |
| - Originarium DB Setup                                                 | • PostgreSQL <br>• Network config <br>• Load balancing                        | 2 weeks                |
| - Unit Tests                                                           | • Development and execution                                                   | 1 week                 |
| - Documentation                                                        | • Technical write-ups <br>• Usage guides <br>• Architecture diagrams          | 0.5 week               |
| - Peer Review                                                          | • Code review by second engineer                                              | 0.5 week               |
| - **Iteration Phase with Qubic Team**                                  | • Review & approval to proceed                                                | 1 week                 |
| <span style="color:#124C89">**2. Curation**</span>                     |                                                                               | **11 weeks**           |
| - Prospection                                                          | • Schema audit <br>• Data type mapping <br>• Semantics pre-validation         | 1 week                 |
| - Development                                                          | • Service (Node.js/Go/Rust)                                                   | 2 weeks                |
| - Architecture Setup                                                   | • VM/containers <br>• Network config <br>• Load balancing                     | 1 weeks                |
| - Deployment                                                           | • Implementation <br>• Resilience <br>• Testing                               | 2 weeks                |
| - Semantide DB Setup                                                   | • PostgreSQL <br>• Schema design <br>• Load balancing                         | 2 weeks                |
| - Unit Tests                                                           | • Development and execution                                                   | 1 week                 |
| - Documentation                                                        | • Data structure notes <br>• Transformation flows                             | 0.5 week               |
| - Peer Review                                                          | • Code audit and review                                                       | 0.5 week               |
| - **Iteration Phase with Qubic Team**                                  | • Feedback and approval to proceed                                            | 1 week                 |
| <span style="color:#124C89">**3. Descriptive Analytics Engine**</span> |                                                                               | **8 weeks**            |
| - Prospection                                                          | • Identify KPIs <br>• Semantic tagging options <br>• Query capabilities       | 1 week                 |
| - Analytical Logic Implementation                                      | • Historical metrics <br>• Address behaviors                                  | 2 weeks                |
| - Semantic Modeling                                                    | • Labeling clusters <br>• Feature engineering                                 | 2 weeks                |
| - Unit Tests                                                           | • Validation of KPIs and metrics                                              | 1 weeks                |
| - Documentation                                                        | • Queries mapping <br>• Metrics catalog                                       | 0.5 week               |
| - Peer Review                                                          | • Review analytical functions                                                 | 0.5 week               |
| - **Iteration Phase with Qubic Team**                                  | • Feedback and green light to proceed                                         | 1 week                 |
| <span style="color:#124C89">**4. Exposure**</span>                     |                                                                               | **10 weeks**           |
| - Prospection                                                          | • NLP agent scope definition <br>• Prompt engineering evaluation              | 1 week                 |
| - Setup & Development                                                  | • MCP setup <br>• Guard prompting agent logic                                 | 2 weeks                |
| - Deployment                                                           | • Logs <br>• Alert integrations <br>• Testing                                 | 2 weeks                |
| - Friend and Family Interaction                                        | • Review and revise feedback                                                  | 2 week                 |
| - Unit Tests                                                           | • Testing response and access logs                                            | 1 weeks                |
| - Documentation                                                        | • NLP flows <br>• User query examples <br>• Permission logic                  | 0.5 week               |
| - Peer Review                                                          | • Prompt engine and access validation                                         | 0.5 week               |
| - **Iteration Phase with Qubic Team**                                  | • Final feedback and handoff                                                  | 1 week                 |

> <span style="color:#124C89">**TOTAL ESTIMATED (Phase 1):**</span> **37 weeks** + 4 weeks for reviewing

> Note: The week allocated to the Iteration Phase with Qubic Team is included in the total project duration of 41 weeks but is excluded from resource allocation calculations. This phase serves as a dedicated period for review, feedback, and approval by the Qubic team.

<br>

### <span style="color:#124C89">Effort Scenarios and Resource Allocation</span>

The total availability of the core team working on TxGuard is structured around a combined capacity of 1.2 Full-Time Equivalents (FTEs). This allocation is distributed among four team members: one person is assigned 60% of their time, while the other three are each assigned 20%. An FTE represents one person working full-time, which typically means 8 hours a day, 5 days a week. Therefore, a capacity of 1.2 FTEs reflects the combined effort of 1.2 full-time team members over the project's timeline. This configuration allows for focused parallel development while ensuring cross-functional input across architecture, data science, engineering, and compliance. All timeline and workload estimates, including the 252 FTE days in the P10 scenario, are based on this available capacity.

To address variability in effort and delivery, three risk-based scenarios are projected:

- **P10 (Best Case)**: 33 weeks
- **P50 (Baseline)**: 37 weeks
- **P90 (Conservative)**: 41 weeks

| Scenario | Duration (weeks) | Jose | Javi | Andrés | Jacky | Total FTE Days |
| -------- | ---------------- | ---- | ---- | ------ | ----- | -------------- |
| P10      | 33               | 57%  | 19%  | 19%    | 19%   | 166            |
| P50      | 37               | 60%  | 20%  | 20%    | 20%   | 185            |
| P90      | 41               | 63%  | 21%  | 21%    | 21%   | 204            |

<br>

### <span style="color:#124C89">Cost Estimation by Scenario</span>

Developer daily rates were benchmarked from Western Europe ([Arc.dev, 2024](https://arc.dev/salaries?location=spain) and [Satatic DevitJobs](https://static.devitjobs.com/market-reports/European-Transparent-IT-Job-Market-Report-2024.pdf?utm_source=chatgpt.com)):

- **P10 (Best Case)**: $125/day
- **P50 (Realistic Case)**: $300/day
- **P90 (Worst Case)**: $450/day

### Phase-Based Effort and Cost Estimation

| Phase                           | P10 Time (weeks) | P50 Time (weeks) | P90 Time (weeks) | P10 Cost (€) | P50 Cost (€) | P90 Cost (€) |
| ------------------------------- | ---------------- | ---------------- | ---------------- | ------------ | ------------ | ------------ |
| 0. RFP Preparation              | 1                | 1                | 1                | 5,000        | 5,000        | 5,000        |
| 1. Collection                   | 9                | 10               | 11               | 5,625        | 15,000       | 24,750       |
| 2. Curation                     | 9                | 10               | 11               | 5,625        | 15,000       | 24,750       |
| 3. Descriptive Analytics Engine | 6                | 7                | 8                | 3,750        | 10,500       | 18,000       |
| 4. Exposure                     | 8                | 9                | 10               | 5,000        | 13,500       | 22,500       |
| **Total**                       | **33**           | **37**           | **41**           | **25,000**   | **59,000**   | **95,000**   |

<br>

# <span style="color:#198110">XVI. Milestones and Estimated Timeline</span>

The following timeline outlines key project milestones and the prices estimation, covering the full scope of **Phase 1: Incubation**.

> Timeline assumes a project start date of **Jun 2025** 2 weeks vacation at the end of August and 2 weeks vacation at the end of December, milestone-based delivery approach with parallel task execution where feasible.

### <span style="color:#124C89">Milestone-to-Phase Alignment Overview</span>

### Milestone-to-Phase Alignment Overview (Adjusted for Holidays)

| Phase                           | Weeks | Cost (€) | Start Date | End Date   |
| ------------------------------- | ----- | -------- | ---------- | ---------- |
| 0. RFP Preparation              | 1     | 5,000    | 2025-06-02 | 2025-06-07 |
| 1. Collection                   | 9     | 5,625    | 2025-06-07 | 2025-08-09 |
| 2. Curation                     | 9     | 5,625    | 2025-08-09 | 2025-10-25 |
| 3. Descriptive Analytics Engine | 6     | 3,750    | 2025-10-25 | 2025-12-06 |
| 4. Exposure                     | 8     | 5,000    | 2025-12-06 | 2026-02-14 |

<br>

# <span style="color:#198110">XVII. Use Cases</span>

The following use cases illustrate how **TxGuard** will serve key actors across the financial compliance lifecycle. Each use case aligns with the platform’s **Phase 1** (descriptive analytics) capabilities, offering a practical view of how blockchain insights can improve operational decision-making and regulatory compliance.

### <span style="color:#124C89">Phase 1: Incubation – Descriptive Analytics and User Interface</span>

#### **Use Case 1: Natural Language Querying for Compliance**

- **Actor**: Compliance Officer
- **Scenario**: Enters the query: “Show me all Qubic transactions over 1M QUBIC last month.”
- **Outcome**: The system returns a structured list of transactions with filters and metadata for investigation.

#### **Use Case 2: Transaction Volume Analysis for Risk Assessment**

- **Actor**: Risk Manager
- **Scenario**: Asks, “What is the average transaction volume per user this quarter?”
- **Outcome**: A visual trend chart and summary table are generated for risk profiling.

#### **Use Case 3: Wallet Activity Overview for Client Profiling**

- **Actor**: Financial Advisor
- **Scenario**: Queries, “List the top 5 active wallets this month.”
- **Outcome**: Ranked list of wallet addresses with associated activity metrics is returned.

#### **Use Case 4: Transaction Monitoring and Pattern Detection**

- **Actor**: Compliance Officer
- **Scenario**: Investigates high-frequency transactions across ticks.
- **Outcome**: Heatmaps and pattern recognition visuals highlight unusual clusters and flows.

#### **Use Case 5: Customer Risk Profiling**

- **Actor**: Risk Analyst
- **Scenario**: Inputs a blockchain identity to assess credit eligibility.
- **Outcome**: Risk score is returned based on transaction history and behavioral patterns.

#### **Use Case 6: Asset Tracing**

- **Actor**: Investigator
- **Scenario**: Needs to track the origin of funds received by a suspicious address.
- **Outcome**: A transaction graph shows the complete inbound tick path across identities.

#### **Use Case 7: Regulatory Reporting**

- **Actor**: Compliance Team
- **Scenario**: Prepares a quarterly AML/KYT report.
- **Outcome**: Auto-generated, exportable reports with key KPIs and customizable filters.

#### **Use Case 8: Fraud Detection via Identity Mapping**

- **Actor**: Fraud Investigator
- **Scenario**: Investigates a scam alert on a specific address.
- **Outcome**: A graph of identity relationships surfaces potential laundering or scam clusters.

<br>

# <span style="color:#198110">XVIII. Annex: Phase 2 Planning – Predictive Capabilities and Compliance</span>

This annex outlines the projected scope and technical expectations for **Phase 2: Acceleration** of the **TxGuard** platform. While the current proposal covers the foundational elements of Phase 1, the second phase is designed to extend the platform’s capabilities with **predictive analytics**, **compliance automation**, and **risk intelligence**, essential for high-stakes financial operations.

The objective is to ensure TxGuard’s long-term relevance by introducing machine learning, anomaly detection, and behavioral modeling as native features. This forward-looking design supports compliance with global regulatory frameworks while positioning TxGuard as a next-generation blockchain intelligence layer.

### <span style="color:#124C89">1. Scope</span>

- **User Management & Access Control for Phase 2**: Leverage Qubic address-based identity with role-based permissions.
- **Future-Proofing for Phase 2**: Design architecture to support predictive analytics scalability.
- **Compliance Features for Phase 2**: Plan for AML/KYT checks and reporting capabilities.

### <span style="color:#124C89">Phase 2: Acceleration (Predictive Analytics)</span>

**Objective**: Augment **TxGuard** with predictive analytics to enhance compliance workflows and risk management.

**Key Activities**:

- Train machine learning models for anomaly detection and trend forecasting.
- Integrate AML/KYT compliance automation features.
- Validate the accuracy and performance of insights generated by the models.

### <span style="color:#124C89">Inputs</span>

- **Client Data**: Identity-linked Know Your Customer (KYC) information.
- **Regulatory Rules**: AML/KYT standards, thresholds, and custom flags.

### <span style="color:#124C89">Outputs</span>

- **Risk Scores**: Near real-time assessments of identity and transaction risk levels.
- **Anomaly Alerts**: Notifications driven by machine learning for suspicious patterns.
- **Model Metrics**: Confidence intervals, accuracy scores, and false positive rates.

### <span style="color:#124C89">Functional Requirements</span>

- **FR6**: Customizable risk scoring algorithms based on frequency, volume, and network behavior.
- **FR7**: Behavioral profiling linked to high-risk entities and address clustering.
- **FR8**: ML-based risk classification models targeting ≥90% accuracy.
- **FR12**: Role-Based Access Control (RBAC) mapped to Qubic identities and subscription tiers.

### <span style="color:#124C89">Non-Functional Requirements</span>

- **NFR4**: AWS auto-scaling support for horizontal scalability.
- **NFR5**: ≥90% uptime with fault-tolerant architecture.
- **NFR6**: Interoperability with external entities using structured formats.
- **NFR7**: GDPR compliance, audit logging, and secure data disposal.
- **NFR8**: WCAG 2.1-compliant interface for non-technical users.
- **NFR9**: End-to-end encryption; PCI DSS and ISO 27001 compliance.

### <span style="color:#198110">VIII. Metrics and KPIs</span>

#### 1. System Performance Metrics

- **Query Response Time**: <10s for 85% of NLP queries.
- **Uptime**: ≥90% (≤3 hours downtime annually).

### 2. User Adoption and Satisfaction

- **Adoption Rate**: ≥80% within 6 months of deployment.

### 3. Compliance and Risk Management

- **Alert Accuracy**: ≥70%.
- **Risk Detection Speed**: <1 minute.
- **Reporting Efficiency**: 50% time reduction.
- **Compliance Coverage**: 100% regulatory alignment.

#### 4. Business Impact

- **Revenue Protection**: ≥70% of fraudulent activity intercepted.
- **Efficiency Improvement**: ≥60% reduction in compliance workload.
- **API Performance**: <100ms for 95% of calls.

#### 5. Security and Compliance

- **Security Incident Rate**: 0 breaches/year.
- **Audit Compliance**: 100% coverage.

#### 6. Innovation and Improvement

- **Feature Velocity**: ≥2 major features/year.
- **Model Accuracy Gain**: +5% per quarter.
- **User Feedback Implementation**: ≥25% of viable feedback delivered within 6 months.

### <span style="color:#124C89">Phase 2: Use Cases</span>

#### **Use Case 9: Compliance Policy Enforcement**

- **Actor**: Compliance Officer
- **Scenario**: Creates custom rules for transaction deviations.
- **Outcome**: System auto-escalates violations and logs audit trails.

#### **Use Case 10: Predictive Transaction Risk Scoring**

- **Actor**: AML Analyst
- **Scenario**: Assesses pre-confirmation transaction risk.
- **Outcome**: High-risk transactions are flagged in real time.

#### **Use Case 11: Anomaly Detection and Early Warnings**

- **Actor**: Fraud Prevention Team
- **Scenario**: Receives alerts on unusual activity spikes.
- **Outcome**: ML models surface early indicators of fraud.

### **Use Case 12: Customer Behavior Forecasting**

- **Actor**: Relationship Manager
- **Scenario**: Tracks behavioral shifts in high-value clients.
- **Outcome**: Predictive models inform engagement strategies.

#### **Use Case 13: Money Laundering Network Analysis**

- **Actor**: AML Team
- **Scenario**: Identifies risk across wallet networks.
- **Outcome**: Illicit clusters are mapped and scored using ML.

<br>

Let´s BUIDL!!

<br><br><br>
