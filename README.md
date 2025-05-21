# <span style="color:#198110">Request for Proposal to Qubic regarding TxGuard</span>

> by DataLedgerLabs (Smashing Blocks)

## Table of Contents

- [Executive Summary](#executive-summary)
- [I. Pain Point Addressed](#i-pain-point-addressed)
- [II. Value Proposition and Differentiation](#ii-value-proposition-and-differentiation)
- [III. Project Overview](#iii-project-overview)
- [IV. Global Functionality and Building Strategy](#iv-global-functionality-and-building-strategy)
- [V. Requirements](#v-requirements)
- [VI. Architecture](#vi-architecture)
- [VII. Metrics and KPIs](#vii-metrics-and-kpis)
- [VIII. Business Model](#viii-business-model)
- [IX. Risk Considerations](#ix-risk-considerations)
- [X. Competitors](#x-competitors)
- [XI. Stakeholder Alignment](#xi-stakeholder-alignment)
- [XII. Marketing and Communication Strategy](#xii-marketing-and-communication-strategy)
- [XIII. The Team](#xiii-the-team)
- [XIV. Budget Estimation](#xiv-budget-estimation)
- [XV. Use Cases](#xv-use-cases)
- [XVI. Annex](#xvi-annex)

---

# <span style="color:#198110">Executive Summary</span>

The financial landscape has evolved clients now use blockchain addresses as identities alongside traditional accounts, engaging in decentralized activities that challenge conventional oversight. Can financial entities truly understand these behaviors while adhering to Anti-Money Laundering (AML) and Know Your Transfer (KYT) standards? **DataLedgerLabs** presents **TxGuard**, a comprehensive **"Business-to-Artificial Intelligence"** (B2AI) solution designed for traditional and non-traditional financial entities. The solution is planned to be built on Amazon Web Services (AWS). **TxGuard** delivers a comprehensive view of financial identities on the **Qubic blockchain**, ensuring compliance with AML and KYT requirements.

TxGuard is structured as a two-phase deployment strategy that maximizes scalability, reduces risk, and ensures rapid value delivery:

- Phase 1 - Incubation: This phase, which is the focus of the present Request for Proposal (RFP), concentrates on data extraction, semantic curation, descriptive analytics, and natural language exposure of Qubic’s tick-level data. It is designed to provide immediate data value and enable intuitive interaction with blockchain datasets via natural language queries, without requiring a user-facing UI.

- Phase 2 - Acceleration: Planned for future execution, this phase will integrate advanced predictive analytics, anomaly detection, and behavioral insights. It aims to elevate compliance efforts and decision-making through machine learning capabilities. A preliminary outline of Phase 2 is included in the annex.

Phase 1 implementation of TxGuard is projected to span 37 weeks, with a core team of 1.2 Full-Time Equivalents (FTEs) across four members. It covers Request for Proposal (RFP) preparation and four core stages: Collection, Curation, Descriptive Analytics Engine, and Exposure. The budget totals €25,000 and aligns with the scope of the first-place submission for the [Madrid Hackathon MAD2025](https://qubic.org/madrid-hackathon). Detailed cost and time allocations are provided in Section [Budget Estimation](#xiv-budget-estimation).

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

We provide both traditional and non-traditional financial institutions with a comprehensive view of a blockchain identity’s financial behavior on the Qubic network.

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

<br>

# <span style="color:#198110">V. Requirements</span>

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

# <span style="color:#198110">VI. Architecture</span>

The data pipeline architecture for **TxGuard** is designed with modularity, fault tolerance, and scalability in mind, leveraging AWS services within a European Virtual Private Cloud (VPC) framework. It separates responsibilities across collection, curation, analytics, and storage to ensure efficient and secure data handling.

> Disclaimer: This architecture is subject to iterative refinement during development consistent with the goals of the first-place submission TxGuard’s design goals and stakeholder feedback, ensuring optimal performance, compliance, and usability for financial entities.

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

# <span style="color:#198110">VII. Metrics and KPIs</span>

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

# <span style="color:#198110">VIII. Business Model</span>

TxGuard’s performance and business success will be measured through a defined set of metrics and key performance indicators (KPIs), including system responsiveness, user satisfaction, compliance impact, and predictive capabilities. These metrics ensure both technical rigor and strategic alignment across the development roadmap, spanning Phase 1 and the more commercially oriented Phase 2.

As this RFP pertains exclusively to Phase 1, the platform will not include a user-facing UX/UI layer. Instead, interaction will be facilitated via a natural language interface powered by a Large Language Model (LLM), enabling database queries without a traditional frontend.

Formal subscription tiers will be introduced in Phase 2, where a fully featured product, starting with a beta version of the Basic Tier, will be released to early users for testing and feedback.

> **Disclaimer**: Final pricing and packaging are subject to a full market study prior to product launch.

<br>

# <span style="color:#198110">IX. Risk Considerations</span>

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

# <span style="color:#198110">X. Competitors</span>

The blockchain analytics landscape is competitive, with several established players offering AML/KYT services. However, **TxGuard** differentiates itself by targeting an underserved segment, **the Qubic ecosystem**, while focusing on accessibility, flexibility, and cost-efficiency. Potential competitors could be considered on most of the data intelligence platforms already in the market such as [chainalysis](https://www.chainalysis.com/chainalysis-kyt-certification/), [ciphertrace](https://www.mastercard.com/global/en/business/issuers/crypto.html), [pixelplex](https://pixelplex.io/know-your-transaction/)

### <span style="color:#124C89">Key Differentiators</span>

- **User-Centric Design**  
  Unlike competitors that require extensive technical knowledge, **TxGuard** features a natural language interface, empowering non-technical users such as compliance officers and financial advisors to interact with complex blockchain data effortlessly.
- **Qubic Ecosystem Focus**  
  **TxGuard** provides a first-mover advantage in the Qubic ecosystem, a rapidly evolving but currently under-analyzed blockchain platform capable of processing over 55 million smart contract executions per second.
- **Cost Efficiency**  
  While platforms like Chainalysis offer potent features, their enterprise pricing may be out of reach for smaller institutions.

<br>

# <span style="color:#198110">XI. Stakeholder Alignment</span>

The success of **TxGuard** relies on strategic alignment among a diverse set of stakeholders. Each group plays a vital role in shaping the platform’s direction, ensuring it meets the technical, compliance, and usability expectations of financial institutions navigating Qubic’s decentralized and tick-based ecosystem.

### <span style="color:#124C89">External Stakeholders</span>

- **Regulatory Bodies**: May audit TxGuard to ensure compliance with blockchain monitoring standards.

- **Qubic´s Identify Owners and Financial Entities (traditional and no-traditional)**: Benefit from actionable insights, transparency, and privacy-compliant services.

- **Technology Partners (e.g., Qubic Network)**: Contribute to performance, scalability, and real-time capabilities.

- **Advisory Partners (e.g., Blockchain Engineers, Compliance Experts, Cybersecurity Consultants)**: Strengthen trust, compliance, and system resilience.

<br>

# <span style="color:#198110">XII. Marketing and Communication Strategy</span>

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

# <span style="color:#198110">XIII. The Team</span>

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

# <span style="color:#198110">XIV. Budget Estimation</span>

This section outlines the estimated effort, staffing, and costs for Phase 1 of TxGuard. It covers RFP preparation and four core stages: Collection, Curation, Descriptive Analytics Engine, and Exposure. The estimates account for infrastructure setup, development, deployment, documentation, and testing. The initial phase adopts a pay-per-query business model, with subscription tiers planned for Phase 2.

### **Staffing and FTE Allocation**

TxGuard’s core team consists of four members with a combined capacity of 1.2 Full-Time Equivalents (FTEs), where one FTE represents a person working full-time (8 hours/day, 5 days/week). The team includes one member at 60% capacity and three at 20% each. This lean team enables parallel development across architecture, data science, engineering, and compliance, optimizing resources for the 33 weeks project timeline.

The hourly rate was set at $15.50, based on a standard 5-day work week. Using this rate, the total project cost is estimated at approximately $25,000. It is important to highlight that the one-week iteration with the Qubic Team at the end of each Phase 1 milestone is included in the 37-week project timeline, but not in the resource cost calculation. These four additional weeks are reserved exclusively for collaborative reviews, feedback, and formal approval with Qubic stakeholders—ensuring strategic alignment without adding development costs.

The following timeline outlines key **project milestones** and the prices estimation, covering the full scope of **Phase 1: Incubation**.

<br>

| Phase / Task                    | Subtasks                                                                  | Time (weeks) | Cost (€)   | Start Date | End Date   |
| ------------------------------- | ------------------------------------------------------------------------- | ------------ | ---------- | ---------- | ---------- |
| 0. RFP Preparation              | Draft RFP, project scoping, repository setup                              | 1            | 5,000      | 06/02/2025 | 06/07/2025 |
| 1. Collection                   | Node validation, service development (Node.js), PostgreSQL setup, testing | 9            | 5,625      | 06/07/2025 | 08/09/2025 |
| 2. Curation                     | Schema audit, service development (Node.js/Go/Rust), Semantic DB setup    | 9            | 5,625      | 08/09/2025 | 10/25/2025 |
| 3. Descriptive Analytics Engine | KPI identification, semantic modeling, metric validation                  | 6            | 3,750      | 10/25/2025 | 12/06/2025 |
| 4. Exposure                     | NLP agent setup, prompt engineering, user query testing                   | 8            | 5,000      | 12/06/2025 | 02/14/2026 |
| **Total (excluding reviews)**   |                                                                           | **33**       | **25,000** |            |            |

<br>

# <span style="color:#198110">XV. Use Cases</span>

The following use cases illustrate how **TxGuard** will serve key actors across the financial compliance lifecycle. Each use case aligns with the platform’s **Phase 1** (descriptive analytics) capabilities, offering a practical view of how blockchain insights can improve operational decision-making and regulatory compliance.

- **Natural language querying for compliance**: Search and retrieve transaction data using plain language questions.

- **Transaction volume analysis**: Visualize and analyze average user volumes for risk profiling.

- **Wallet activity overview**: Identify and rank the most active wallets over a time period.

- **Transaction pattern detection**: Detect anomalies via heatmaps and behavioral clustering.

- **Customer risk profiling**: Assess wallet risk scores based on behavioral and historical patterns.

- **Asset tracing**: Trace the origin and flow of funds across wallet identities.

- **Regulatory reporting**: Generate exportable AML/KYT reports with key performance indicators.

- **Fraud detection via identity mapping**: Uncover suspicious clusters using identity relationship graphs.

<br>

---

# <span style="color:#198110">XVI. Annex

### <span style="color:#198110">Inputs and Outputs Phase 1: Incubation</span>

**TxGuard’s** ability to deliver actionable insights relies on a clearly defined flow of inputs and outputs that processes Qubic’s tick-based blockchain data and translates it into usable intelligence. The following outlines the key data inputs and resulting outputs across both deployment phases.

#### <span style="color:#124C89">1. Inputs</span>

- **Tick Data**: Qubic transaction logs, tick headers, and metadata
- **User Queries**: Natural language prompts and structured search inputs
- **Configuration Parameters**:
  - Transaction history range
  - Preferred output formats
  - Security guardrails and filters

#### <span style="color:#124C89">2. Outputs</span>

- **Transaction Insights**: Summaries and key metrics (e.g., transaction volume, frequency, address activity)
- **Query Responses**: Structured results (e.g., tabular, JSON) aligned with user prompts
- **Audit Logs**: Logs capturing user activity and access for traceability

### <span style="color:#124C89"> Phase 2 Planning – Predictive Capabilities and Compliance</span>

This annex outlines the projected scope and technical expectations for **Phase 2: Acceleration** of the **TxGuard** platform. While the current proposal covers the foundational elements of Phase 1, the second phase is designed to extend the platform’s capabilities with **predictive analytics**, **compliance automation**, and **risk intelligence**, essential for high-stakes financial operations.

The objective is to ensure TxGuard’s long-term relevance by introducing machine learning, anomaly detection, and behavioral modeling as native features. This forward-looking design supports compliance with global regulatory frameworks while positioning TxGuard as a next-generation blockchain intelligence layer.

#### <span style="color:#124C89">Scope</span>

- **User Management & Access Control for Phase 2**: Leverage Qubic address-based identity with role-based permissions.
- **Future-Proofing for Phase 2**: Design architecture to support predictive analytics scalability.
- **Compliance Features for Phase 2**: Plan for AML/KYT checks and reporting capabilities.

#### <span style="color:#124C89">Phase 2: Acceleration (Predictive Analytics)</span>

**Objective**: Augment **TxGuard** with predictive analytics to enhance compliance workflows and risk management.

**Key Activities**:

- Train machine learning models for anomaly detection and trend forecasting.
- Integrate AML/KYT compliance automation features.
- Validate the accuracy and performance of insights generated by the models.

#### <span style="color:#124C89">Inputs</span>

- **Client Data**: Identity-linked Know Your Customer (KYC) information.
- **Regulatory Rules**: AML/KYT standards, thresholds, and custom flags.

#### <span style="color:#124C89">Outputs</span>

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

### <span style="color:#198110">Metrics and KPIs</span>

#### 1. System Performance Metrics

- **Query Response Time**: <10s for 85% of NLP queries.
- **Uptime**: ≥90% (≤3 hours downtime annually).

#### 2. User Adoption and Satisfaction

- **Adoption Rate**: ≥80% within 6 months of deployment.

#### 3. Compliance and Risk Management

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

### <span style="color:#124C89">Business Model Phase 2: Subscription Tiers</span>

- **Basic Tier**
  - Access to core descriptive analytics
  - Limited query capabilities
- **Optimal Tier**
  - Full access to all **Phase 1** features
  - Natural language querying extended
- **Comprehensive Tier**
  - Includes **Phase 2** capabilities
  - Predictive analytics and full AML/KYT compliance support

### <span style="color:#124C89">Phase 2: Use Cases</span>

**Compliance policy enforcement**: Define and monitor custom rules to automatically flag violations.

**Predictive transaction risk scoring**: Flag high-risk transactions before confirmation using risk models.

**Anomaly detection and early warnings**: Detect abnormal activity spikes through real-time ML alerts.

**Customer behavior forecasting**: Anticipate behavioral shifts in key clients to optimize engagement.

**Money laundering network analysis**: Map and score suspicious wallet clusters using identity-aware ML.

<br><br><br>
