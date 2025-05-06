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

---

# <span style="color:#198110">Executive Summary</span>

The financial landscape has evolved—clients now use blockchain addresses as identities alongside traditional accounts, engaging in decentralized activities that challenge conventional oversight. Can financial entities truly understand these behaviors while adhering to Anti-Money Laundering (AML) and Know Your Transfer (KYT) standards? **DataLedgerLabs** presents **TxGuard**, a comprehensive Business-to-Intelligence Artificial (**B2IA**) solution designed for traditional and non-traditional financial entities. The solution is planned to be built on Amazon Web Services (AWS). **TxGuard** delivers a comprehensive view of financial identities on the **Qubic blockchain**, ensuring compliance with AML and KYT requirements.

This Request for Proposal (RFP) outlines a two-phase deployment strategy that is designed to ensure a smooth and effective implementation of TxGuard, maximizing its benefits for users and stakeholders.

1.  **Phase 1 (Incubation, 8–12 months)**  
    Extract, curate, assemble descriptive analytic and exposed **Qubic** tick data, provide data value, and enable natural language querying for seamless access.
2.  **Phase 2 (Acceleration)**  
    Introduce predictive analytics for anomaly detection and trend forecasting, enhancing decision-making and compliance efforts.

**TxGuard** taps into a USD 2.89 billion blockchain analytics market within the USD 57.72 billion global blockchain technology market in 2025, with a projected CAGR of 90.1% through 2030 ([Grand View Research, 2024](https://www.grandviewresearch.com/industry-analysis/blockchain-technology-market)). Qubic’s quorum-based computation and tick system processes up to 55 million transactions per second ([The Qubic Team, 2024](https://qubic.org/blog-detail/qubic-achieves-over-55-million-transfers-per-second-for-smart-contract-executions)), positioning **TxGuard** as a first-mover in an underserved ecosystem. The potential impact of this solution is significant, offering a unique opportunity to be at the forefront of blockchain compliance.

<br>

# <span style="color:#198110">I. Pain Point Addressed</span>

The rules have changed: clients are no longer defined solely by bank accounts—they now possess blockchain identities that reflect their decentralized financial activities. Financial entities face a critical challenge: how can they understand these identities while ensuring compliance with AML and KYT regulations? **TxGuard** addresses this pain point by:

- Providing a comprehensive view of **financial behavior on the Qubic blockchain**.
- Transforming complex, anonymous data into clear, **actionable insights**.
- **Enabling secure, data-driven decisions** for fraud prevention, compliance, and market intelligence.

By bridging traditional finance with blockchain ecosystems, **TxGuard** ensures financial institutions can confidently navigate this emerging landscape while aligning with global compliance standards.

<br>

# <span style="color:#198110">II. Value Proposition and Differentiation</span>

### <span style="color:#124C89">How We Differentiate TxGuard</span>

**TxGuard** stands out by combining automation, advanced analytics, and user-centric design to deliver unmatched value in the current market:

- **Automation**: Automated data ingestion and transformation pipelines using AWS tools reduce manual effort, ensuring efficiency and scalability.

- **Cost-Performance Harmony**: Tiered pricing models (Basic, Optimal, Comprehensive) balance technical capability with affordability, making the solution accessible.

- **Natural Language Interface**: An intuitive natural language consultation feature allows users (IAs, entities, or Qubic blockchain partners) to query complex blockchain data without specialized technical knowledge—enhancing accessibility and decision-making.

- **Secure Cloud Infrastructure**: Built on AWS, the solution offers enterprise-grade security, scalability, and reliability for handling sensitive financial data and high-volume blockchain analytics ([AWS Web3 Blog, 2024](https://aws.amazon.com/blogs/web3/)).

- **Descriptive Analytics Foundation**: The Dapp provides robust descriptive key variables and insights into transaction patterns and customer behaviour.

- **Customizable Insights**: The user can parameterize the variables they desire to extract so they can meet their specific needs.

- **Enhanced Regulatory Compliance**: **_Phase 2_** builds on this with near real-time insights by leveraging curated blockchain data for AML and KYT compliance. This proactive approach helps financial entities stay ahead of regulatory demands and positions them for effective risk management and fraud detection in non-traditional assets inspired by [Chainalysis KYT, 2025](https://www.chainalysis.com/product/kyt/).

<span style="color:#124C89">**Value Proposition**</span>

**TxGuard** empowers Qubic's owner identities and financial entities with blockchain intelligence, addressing fraud prevention and market insight needs in a growing analytics market valued at USD 2.89 billion in 2025, within a global blockchain market projected at USD 57.72 billion ([Grand View Research, 2024](https://www.grandviewresearch.com/industry-analysis/blockchain-technology-market)). Starting with **Qubic**, the platform provides a first-mover advantage with scalability toward broader blockchain networks ([101blockchains.com, 2025](https://101blockchains.com/top-blockchain-analytics-companies/)).

<br>

# <span style="color:#198110">III. Project Overview</span>

**TxGuard** is a decentralized application (Dapp) delivering descriptive analytics and natural language querying of Qubic tick data, covering transaction patterns, identities behaviours, and risk factors. It enhances regulatory compliance, sharpens decision-making, and sets the stage for predictive analytics.

- **Phase 1 (Incubation)**: Establish a robust pipeline for tick data extraction, curation, and descriptive analytics with natural language access.

- **Phase 2 (Acceleration)**: Add predictive models for anomaly detection and trend forecasting, amplifying AML/KYT capabilities.

- **Target Users**: Qubic´s owner identity, financial entities, compliance officers, risk managers, and investment strategists seeking actionable blockchain insights.

## <span style="color:#124C89">1. Scope</span>

- **Tick Data Extraction & Curation**: Extract Qubic tick data (e.g., transaction logs) and curate it for accuracy and relevance.
- **Natural Language Interface**: Enable intuitive querying of tick data in plain language (English).

- **Descriptive Analytics Engine**: Compute metrics like transaction volume and frequency for **_Phase 1_** insights.

- **AWS Cloud Infrastructure**: Host a secure, scalable Dapp environment on AWS.

- **Integration Capabilities**: Provide a system for syncing with existing systems.

- **Documentation & Training**: Supply comprehensive user guides and training sessions.

- **User Management & Access Control for Phase 2**: Leverage Qubic address-based identity with role-based permissions**_._**

- **Future-Proofing for Phase 2**: Design architecture to support predictive analytics scalability.

- **Compliance Features for Phase 2**: Plan for AML/KYT checks and reporting capabilities.

<br>

## <span style="color:#124C89">2. Out of Scope</span>

- Development of predictive analytics models (reserved for Phase 2)
- Integration and services for specific third-party financial entities.
- Query languages beyond English.
- Include the 100% of Qubic's ticks information.

<br>

# <span style="color:#198110">IV. Global Functionality and Building Strategy</span>

TxGuard’s development is strategically divided into Phase 1 (Incubation) and Phase 2 (Acceleration) to ensure a structured, efficient, and risk-mitigated approach. The high-level functionality is described below:

## <span style="color:#124C89">Phase 1: Incubation (8–12 Months)</span>

**TxGuard’s Phase 1 (Incubation)** functionality is structured around four core components—**Collection**, **Curation**, **Descriptive Analytics Engine**, and **Exposure**. These modules are designed to establish a strong foundation for Qubic tick data processing and analytics, enabling financial institutions to derive actionable insights for compliance, fraud detection, and market intelligence.

- **Collection**  
  Ingests raw Qubic tick data—including transaction logs, tick headers, and metadata—via a Qubic Archive, and stores it for processing.
- **Data Curation**  
  Cleans, enriches, and unifies incoming tick data formats. Applies semantic enhancements to support advanced querying and pattern recognition.
- **Descriptive Analytics Engine**  
  Processes curated data to generate key metrics and behavioral patterns relevant to use cases such as transaction monitoring, risk analysis, and customer profiling.
- **Exposure**  
  Develops and configures MCPs (Multi-Component Pipelines) and intelligent agents to interpret and respond to user queries in natural language.

<br>

![Phase1](https://github.com/user-attachments/assets/f7f7d7eb-afed-4df9-bd28-5c86e87e2e71)

<br>

> **Out of Scope**:  
> Full UI/UX design, external security audits, and third-party platform integrations

These components work cohesively to deliver reliable, explainable, and structured financial intelligence from decentralized blockchain data. As outlined in previous sections, **predictive modelling, risk scoring, and advanced user role functionalities are planned for Phase 2**.

## <span style="color:#124C89">Phase 2: Acceleration (Predictive Analytics)</span>

**Objective**: Augment **TxGuard** with predictive analytics to enhance compliance workflows and risk management.
**Key Activities**:

- Train machine learning models for anomaly detection and trend forecasting
- Integrate AML/KYT compliance automation features
- Validate the accuracy and performance of insights generated by the models

The diagram below illustrates a simplified schematic of the overall process:

<br>

![OverviewTxGuard](https://github.com/user-attachments/assets/aae1f372-ead1-4fa8-afd9-a3d338b3f8a7)

<br>

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

### **Phase 2: Predictive Analytics**

- **Client Data**: Identity-linked Know Your Customer (KYC) information
- **Regulatory Rules**: AML/KYT standards, thresholds, and custom flags

## <span style="color:#124C89">2. Outputs</span>

### **Phase 1: Descriptive Results**

- **Transaction Insights**: Summaries and key metrics (e.g., transaction volume, frequency, address activity)
- **Query Responses**: Structured results (e.g., tabular, JSON) aligned with user prompts
- **Audit Logs**: Logs capturing user activity and access for traceability

### **Phase 2: Predictive Outcomes**

- **Risk Scores**: Near real-time assessments of identity and transaction risk levels
- **Anomaly Alerts**: Notifications driven by machine learning for suspicious patterns
- **Model Metrics**: Confidence intervals, accuracy scores, and false positive rates

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
- **FR6** (_Phase 2_): Develop customizable risk scoring algorithms using transaction frequency, volume, and network behaviour
- **FR7** (_Phase 2_): Generate entity profiles based on behavioural patterns and links to high-risk addresses
- **FR8** (_Phase 2_): Deploy ML models to detect risk and anomalies, achieving ≥90% accuracy in transaction risk classification
- **FR12** (_Phase 2_): Implement role-based access control (RBAC) linked to Qubic identities and subscription tiers (Basic, Optimal, Comprehensive)

## <span style="color:#124C89">2. Non-Functional Requirements</span>

- **NFR1**: Support >100 concurrent users; return 75% of query responses in under 10 seconds
- **NFR2**: Ensure data integrity via validation, duplication checks, and error handling
- **NFR3**: Modular system architecture with comprehensive documentation and CI/CD readiness
- **NFR4** (_Phase 2_): Enable horizontal scalability using AWS auto-scaling services
- **NFR5** (_Phase 2_): Guarantee 90% system uptime (~<1 hour downtime/year) through fault-tolerant architecture
- **NFR6** (_Phase 2_): Ensure interoperability with external financial entities via structured formats
- **NFR7** (_Phase 2_): Comply with GDPR and other privacy regulations; implement audit logging and secure data deletion
- **NFR8** (_Phase 2_): Design an accessible UI compliant with WCAG 2.1, targeting non-technical users
- **NFR9** (_Phase 2_): Enforce encryption in transit and at rest; comply with PCI DSS and ISO 27001; conduct security audits and enforce key management protocols

<br>

# <span style="color:#198110">VII. Architecture</span>

The data pipeline architecture for **TxGuard** is designed with modularity, fault tolerance, and scalability in mind—leveraging AWS services within a European Virtual Private Cloud (VPC) framework. It separates responsibilities across collection, curation, analytics, and storage to ensure efficient and secure data handling.

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

**TxGuard’s** performance and business success will be continuously evaluated using a defined set of metrics and key performance indicators (KPIs). These span system responsiveness, user satisfaction, compliance impact, and predictive capability—ensuring both technical rigor and organizational alignment across **Phase 1** and **Phase 2**.

### <span style="color:#124C89">1. System Performance Metrics</span>

- **Data Processing Speed**: Average processing time for new Qubic tick transactions
  - _Target_: < 10 seconds for 90% of transactions
- **Data Accuracy**: Percentage of tick data accurately ingested and processed
  - _Target_: ≥ 99.999%
- **Query Response Time** (_Phase 2_): Time to return NLP-based query results
  - _Target_: < 10 seconds for 85% of user prompts
- **System Uptime and Reliability** (_Phase 2_):
  - _Target_: ≥ 90% uptime (no more than 3 hours of downtime annually)

### <span style="color:#124C89">2. User Adoption and Satisfaction Metrics</span>

- **User Adoption Rate**: Percentage of financial entity users actively engaged
  - _Target_: ≥ 80% within 6 months of deployment
- **User Satisfaction Score**: Overall satisfaction on a 1–10 scale
  - _Target_: ≥ 7.5
- **Feature Utilization Rate**: Percentage of features used monthly
  - _Target_: ≥ 70% of features used at least once per month

### <span style="color:#124C89">3. Compliance and Risk Management Metrics (_Phase 2_)</span>

- **Alert Accuracy**: Validated alerts vs. false positives
  - _Target_: ≥ 70%
- **Risk Detection Speed**: Time to flag high-risk activity
  - _Target_: < 1 minute
- **Regulatory Reporting Efficiency**: Time saved in generating compliance reports
  - _Target_: 50% reduction compared to manual workflows
- **Compliance Coverage**: AML/KYT requirements addressed
  - _Target_: 100% regulatory alignment (e.g., FINTRAC, FATF)

### <span style="color:#124C89">4. Business Impact Metrics</span>

- **Revenue Protection (_Phase 2_)**: Value of fraud prevented
  - _Target_: ≥ 70% of flagged fraudulent activity intercepted
- **Efficiency Improvement (_Phase 2_)**: Reduction in time spent on compliance tasks
  - _Target_: ≥ 60%
- **API Performance**: Response time and throughput
  - _Target_: < 100 ms for 95% of API calls

### <span style="color:#124C89">5. Security and Compliance Metrics</span>

- **Security Incident Rate (_Phase 2_)**: Successful breaches or unauthorized access attempts
  - _Target_: 0 incidents per year
- **Audit Compliance (_Phase 2_)**: Coverage of internal and external audit requirements
  - _Target_: 100%

### <span style="color:#124C89">6. Innovation and Improvement Metrics</span>

- **Feature Development Velocity**: Major feature releases
  - _Target_: ≥ 2 per year
- **Model Accuracy Improvement (_Phase 2_)**: Predictive model performance over time
  - _Target_: +5% per quarter
- **User Feedback Implementation (_Phase 2_)**: Suggestions implemented from user base
  - _Target_: ≥ 25% of viable feedback delivered within 6 months

<br>

# <span style="color:#198110">IX. Business Model</span>

**TxGuard’s** performance and business success will be continuously assessed using a defined set of metrics and key performance indicators (KPIs). These metrics will include system responsiveness, user satisfaction, compliance impact, and predictive capability, ensuring both technical rigour and organizational alignment across **Phase 1** and **Phase 2**.

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

The successful deployment of TxGuard—especially during Phase 1—relies on the proactive identification and mitigation of technical, operational, and regulatory risks. Below is a comprehensive risk mitigation strategy that aligns with AWS best practices and ensures the resilience of the blockchain infrastructure.

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

The blockchain analytics landscape is competitive, with several established players offering AML/KYT services. However, **TxGuard** differentiates itself by targeting an underserved segment—**the Qubic ecosystem**—while focusing on accessibility, flexibility, and cost-efficiency. Potential competitors could be considered on most of the data intelligence platforms already in the market such as [chainalysis](https://www.chainalysis.com/chainalysis-kyt-certification/), [ciphertrace](https://www.mastercard.com/global/en/business/issuers/crypto.html), [pixelplex](https://pixelplex.io/know-your-transaction/)

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

---

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

## <span style="color:#124C89">[Andrés León](https://www.linkedin.com/in/andres-leon-bohorquez/) – Senior Backend Architect and Blockchain Educator</span>

With over 20 years of experience in backend systems and distributed architectures, Andrés began coding in BASIC at age 11. He discovered cryptographic systems and digital payments in 2005 through RipplePay at the Polytechnic University, which sparked his commitment to decentralized infrastructure. A professor at CodeCrypto Academy, Andrés is a cornerstone in TxGuard’s architecture—designing scalable systems for tick data ingestion and processing.
**Expertise**: Databases, backend performance, secure systems, distributed ledgers.

## <span style="color:#124C89">[Jacky Barraza](https://www.linkedin.com/in/jackybarraza/) – Senior Data Scientist</span>

Jacky brings 18+ years of experience in AI and cloud-native data engineering. She holds a Master’s in Blockchain Engineering from CodeCrypto Academy and has led predictive analytics projects across finance, energy, and digital identity. Her leadership on **Bloodchain**, a privacy-preserving blockchain system, reflects her commitment to secure, explainable AI. In TxGuard, she drives anomaly detection, compliance scoring, and data modelling.
**Expertise**: Machine learning, Azure ML, decentralized architectures, analytics pipelines.

## <span style="color:#124C89">[Jose Fco Gámez](https://www.linkedin.com/in/dalzemag/) – Senior Solution Architect</span>

Jose has over 15 years of experience across IoT, backend platforms, CTO and DevOps. A Master’s student in Blockchain Engineering, he specializes in cloud-native architecture and CI/CD workflows. His experience spans Shopify, MongoDB, and secure API design. At TxGuard, Jose ensures infrastructure resilience and service modularity.
**Expertise**: AWS, DevOps pipelines, secure APIs, MQTT/Node-RED integration.

## <span style="color:#124C89">[Javier Ruiz-Canela López](https://www.linkedin.com/in/javier-ruiz-canela-lopez-a293a1a3/) – Senior Software Engineer</span>

Javier brings a decade of experience in regulated sectors such as finance and pharmaceuticals. As a Master’s student in Blockchain Engineering, he applies his knowledge of Java, Spring, and secure identity systems (Keycloak, LDAP) to ensure TxGuard’s IAM and analytics services are enterprise-grade.
**Expertise**: Microservices, IAM systems, event-driven architecture, Spring Boot, Kafka.

<br>

# <span style="color:#198110">XV. Budget Estimation</span>

This section provides a high-level breakdown of the estimated effort and cost required to implement **Phase 1** of the TxGuard platform. The estimates cover all functional stages—**Collection**, **Curation**, **Analytics**, and **Exposure**—including infrastructure, development, deployment, and testing.

### <span style="color:#124C89">Development Effort by Phase and Task</span>

<br>

| **Phase / Task**                                                | Subtasks                                                                      | Estimated Time (days) |
| --------------------------------------------------------------- | ----------------------------------------------------------------------------- | --------------------- |
| <span style="color:#124C89">**1. Collection**                   |                                                                               | **50 days**           |
| - Prospection                                                   | • Node access validation <br>• Tick log inspection <br>• Data sync validation | 4 days                |
| - Development                                                   | • Service development (Node.js)                                               | 14 days               |
| - Architecture Setup                                            | • VM/containers <br>• Network config <br>• Load balancing                     | 6 days                |
| - Deployment                                                    | • Implementation <br>• Resilience <br>• Testing                               | 6 days                |
| - Originarium DB Setup                                          | • PostgreSQL <br>• Network config <br>• Load balancing                        | 8 days                |
| - Unit Tests                                                    | • Development and execution                                                   | 4 days                |
| - Documentation                                                 | • Technical write-ups <br>• Usage guides <br>• Architecture diagrams          | 5 days                |
| - Peer Review                                                   | • Code review by second engineer                                              | 3 days                |
| <span style="color:#124C89">**2. Curation**                     |                                                                               | **52 days**           |
| - Prospection                                                   | • Schema audit <br>• Data type mapping <br>• Semantics pre-validation         | 4 days                |
| - Development                                                   | • Service (Node.js/Go/Rust)                                                   | 16 days               |
| - Architecture Setup                                            | • VM/containers <br>• Network config <br>• Load balancing                     | 6 days                |
| - Deployment                                                    | • Implementation <br>• Resilience <br>• Testing                               | 6 days                |
| - Semantide DB Setup                                            | • PostgreSQL <br>• Schema design <br>• Balancing                              | 8 days                |
| - Unit Tests                                                    | • Development and execution                                                   | 4 days                |
| - Documentation                                                 | • Data structure notes <br>• Transformation flows                             | 5 days                |
| - Peer Review                                                   | • Code audit and review                                                       | 3 days                |
| <span style="color:#124C89">**3. Descriptive Analytics Engine** |                                                                               | **42 days**           |
| - Prospection                                                   | • Identify KPIs <br>• Semantic tagging options <br>• Query capabilities       | 4 days                |
| - Analytical Logic Implementation                               | • Historical metrics <br>• Addressiors                                  | 10 days               |
| - Semantic Modeling                                             | • Labeling clusters <br>• Feature engineering                                 | 6 days                |
| - Dashboard Configuration                                       | • Streamlit dashboard setup                                                   | 6 days                |
| - Unit Tests                                                    | • Validation of KPIs and metrics                                              | 6 days                |
| - Documentation                                                 | • Queries mapping <br>• Metrics catalog                                       | 5 days                |
| - Peer Review                                                   | • Review analytical functions                                                 | 3 days                |
| <span style="color:#124C89">**4. Exposure**                     |                                                                               | **50 days**           |
| - Prospection                                                   | • NLP agent scope definition <br>• Prompt engineering evaluation              | 4 days                |
| - Setup & Development                                           | • MCP setup <br>• Guard prompting agent logic                                 | 20 days               |
| - Deployment                                                    | • Logs <br>• Alert integrations <br>• Testing                                 | 10 days               |
| - Unit Tests                                                    | • Testing response and access logs                                            | 6 days                |
| - Documentation                                                 | • NLP flows <br>• User query examples <br>• Permission logic                  | 5 days                |
| - Peer Review                                                   | • Prompt engine and access validation                                         | 3 days                |
| <span style="color:#124C89">**TOTAL ESTIMATED (Phase 1)**       |                                                                               | **194 days**          |

<br>

### <span style="color:#124C89">Effort Scenarios and Resource Allocation</span>

The total availability of the core team working on TxGuard is structured around a combined capacity of 1.2 Full-Time Equivalents (FTEs). This allocation is distributed among four team members: one person is assigned 60% of their time, while the other three are each assigned 20%. An FTE represents one person working full-time, which typically means 8 hours a day, 5 days a week. Therefore, a capacity of 1.2 FTEs reflects the combined effort of 1.2 full-time team members over the project's timeline. This configuration allows for focused parallel development while ensuring cross-functional input across architecture, data science, engineering, and compliance. All timeline and workload estimates, including the 199.5 FTE days in the P10 scenario, are based on this available capacity.

To address variability in effort and delivery, three risk-based scenarios are projected:

- **P10 (Optimistic)**: 175 days
- **P50 (Baseline)**: 194 days
- **P90 (Conservative)**: 213 days

| Scenario | Duration (days) | Jose | Javi | Andrés | Jacky | Total FTE Days |
| -------- | --------------- | ---- | ---- | ------ | ----- | -------------- |
| P10      | 175             | 57%  | 19%  | 19%    | 19%   | 199.5          |
| P50      | 194             | 60%  | 20%  | 20%    | 20%   | 232.8          |
| P90      | 213             | 63%  | 21%  | 21%    | 21%   | 268.3          |

<br>

### <span style="color:#124C89">Cost Estimation by Scenario</span>

Developer daily rates were benchmarked from Western Europe ([Arc.dev, 2024](https://arc.dev/salaries?location=spain) and [Satatic DevitJobs](https://static.devitjobs.com/market-reports/European-Transparent-IT-Job-Market-Report-2024.pdf?utm_source=chatgpt.com)):

- **P10 (Best Case)**: $150/day
- **P50 (Realistic Case)**: $300/day
- **P90 (Worst Case)**: $450/day

| Category                      | % Allocation | P10 Budget (USD) | P50 Budget (USD) | P90 Budget (USD) |
| ----------------------------- | ------------ | ---------------- | ---------------- | ---------------- |
| Architecture & Infrastructure | 15%          | $3,750           | $10,476          | $18,110          |
| Core Development              | 35%          | $8,750           | $24,444          | $42,257          |
| Documentation & QA            | 10%          | $2,500           | $6,984           | $12,074          |
| Peer Review & Governance      | 7%           | $1,750           | $4,889           | $8,452           |
| Project Management            | 9%           | $2,250           | $9,079           | $15,695          |
| Marketing & Community         | 7%           | $1,750           | $6,984           | $12,074          |
| Contingency                   | 7%           | $1,750           | $6,984           | $12,074          |
| **Total**                     | **100%**     | **$25,000**      | **$69,840**      | **$120,735**     |

<br>

# <span style="color:#198110">XVI. Milestones and Estimated Timeline</span>

The following timeline outlines key project milestones and estimated delivery dates across a 12-month window, covering the full scope of **Phase 1: Incubation**. The schedule accounts for development, infrastructure setup, analytics engine deployment, and the initial launch of the natural language interface.

> Timeline assumes a project start date of **May 2025** and follows a linear, milestone-based delivery approach with parallel task execution where feasible.

### <span style="color:#124C89">Milestone-to-Phase Alignment Overview</span>

| Month                   | Key Activities                                              | Phase(s) Covered             |
| ----------------------- | ----------------------------------------------------------- | ---------------------------- |
| **May 2025**            | Kickoff, AWS setup, project alignment                       | Collection                   |
| **June 2025**           | Connect to **Archive Qubic**, deploy ingestion microservice | Collection                   |
| **July–Aug 2025**       | Curation pipeline development, semantic schema definition   | Curation                     |
| **Sept–Oct 2025**       | KPI logic, query layer, dashboard configuration             | Descriptive Analytics Engine |
| **Nov 2025 – Jan 2026** | MCP and NLP agent setup, prompt training                    | Exposure                     |
| **Feb 2026**            | QA testing, feedback integration                            | Testing & QA                 |
| **Mar–Apr 2026**        | Beta testing, onboarding, public release                    | Beta & Launch                |

<br>

# <span style="color:#198110">XVII. Use Cases</span>

The following use cases illustrate how **TxGuard** will serve key actors across the financial compliance lifecycle. Each use case aligns with the platform’s **Phase 1** (descriptive analytics) or **Phase 2** (predictive intelligence) capabilities, offering a practical view of how blockchain insights can improve operational decision-making and regulatory compliance.

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

### <span style="color:#124C89">Phase 2: Acceleration – Predictive Analytics for AML & KYT</span>

#### **Use Case 4: Compliance Policy Enforcement**

- **Actor**: Compliance Officer
- **Scenario**: Creates custom rules to flag deviations in transaction behavior.
- **Outcome**: The system auto-escalates violations and logs actions taken.

#### **Use Case 5: Predictive Transaction Risk Scoring**

- **Actor**: AML Analyst
- **Scenario**: Evaluates transactions in real-time to identify pre-confirmation risks.
- **Outcome**: Transactions with high predicted risk are intercepted and flagged.

#### **Use Case 6: Anomaly Detection and Early Warnings**

- **Actor**: Fraud Prevention Team
- **Scenario**: Requests proactive alerts for unusual transaction spikes or patterns.
- **Outcome**: ML models identify and surface early fraud indicators.

<br><br><br>
