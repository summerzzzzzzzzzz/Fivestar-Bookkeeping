# Allocator Bookkeeping Repository for Fivestar

## Allocator JSON Link
[Link to Fivestar Allocator JSON](https://github.com/filecoin-project/Allocator-Registry/tree/main/Allocators/Fivestar)  
*Note: Replace with the actual link to your allocator JSON once available in the Allocator-Registry.*

## Client Diligence
Fivestar employs a robust client diligence process to verify clients and establish trust while mitigating Sybil attacks, with additional rigor inspired by the HK CyberPort pathway:

- **Business Verification**: Clients must submit registration certificates, incorporation details, company documents, government-issued business ID numbers, and verification of authorized signers (e.g., board approval or CFO letters). For clients under the HK CyberPort pathway, proof of cooperation with Cyberport (e.g., MoU, investment letter) is required.
- **Personal Verification**: Individuals must provide a government-issued photo ID (e.g., passport) and a facial photo alongside the ID for identity confirmation.
- **Voice/Video Verification**: Clients undergo a voice or video meeting to further validate identity and intent, ensuring alignment with Filecoin Plus goals.
- **Sybil Attack Mitigation**: We enforce rate limits on DataCap requests, cap total allocation at **1 PiB** per client, and use [DataCapStats.io](https://datacapstats.io) to monitor allocation patterns for suspicious activity. A `check bot` is activated during working hours to monitor client activity in real-time.
- **Enterprise Data Ownership**: For enterprise clients, we verify data ownership through legal documentation, contracts, or attestations. Data samples are reviewed for compliance with program scope.
- **Audit Evidence**: All KYB/KYC documentation, proof of Cyberport cooperation (if applicable), allocation records, and communication logs are archived and made available to the Filecoin Plus (Fil+) Governance Team for auditing.

## Description of Data Diligence
Fivestar ensures client data aligns with Filecoin Plus program scope and legal requirements, incorporating best practices from the HK CyberPort pathway:

- **Data Ownership Verification**: Clients provide legal contracts, IP documentation, or signed attestations to prove data ownership. For public datasets, we verify open-access status via public repositories or trusted sources. Clients under the CyberPort pathway must submit data samples for compliance review.
- **Legal Compliance**: Clients confirm adherence to local and regional regulations, with data distributed across **3–4 geographic regions** to meet jurisdictional diversity. We verify the geographic distribution of cooperating storage providers (SPs).
- **Data Sampling**: Random sampling is conducted during storage operations using the CID Checker Bot to ensure data in deals matches client claims. [DataCapStats.io](https://datacapstats.io) monitors deal integrity and compliance.
- **Tools Used**: [DataCapStats.io](https://datacapstats.io) for allocation tracking and CID Checker Bot for content verification.
- **Audit Proof**: Detailed logs of data sampling, compliance checks, storage deal metadata, and retrieval rate verification are maintained for Fil+ Governance Team audits.

## Short Description of Pathway for Clients
Choose Fivestar for a transparent, efficient, and client-focused DataCap allocation process, enhanced by our alignment with high-compliance frameworks like the HK CyberPort pathway. We serve small-scale developers, enterprise data clients, and Web3 startups, including those incubated by Cyberport, with a focus on public and private datasets for non-profit and social impact initiatives. Our rigorous KYB/KYC, video verification, and phased allocation (10%–50%, capped at 1 PiB) ensure trust and compliance. With tools like [DataCapStats.io](https://datacapstats.io) and a responsive dispute resolution process, we prioritize accountability and secure storage across diverse regions.

## Contact Info
- **Slack**: Join our Slack channel at `#luster` for direct support.
- **Email**: Contact us at [852711390@qq.com](mailto:852711390@qq.com).
- **GitHub Issues**: Open an issue on our [GitHub repository](https://github.com/summerzzzzzzzzzz) for inquiries or support.

## Detailed Allocator Policies, Procedures, and Requirements
- **Target Clients**: Small-scale developers, enterprise data clients, individuals learning about Filecoin, and Web3 startups incubated, accelerated, or funded by Hong Kong Cyberport.
- **Supported Data Types**: Public open datasets (research/non-profit), public commercial/enterprise data, private commercial/enterprise data, and private non-profit/social impact data.
- **KYB/KYC Requirements**:
  - Business: Registration certificates, incorporation details, government-issued business IDs, authorized signer verification, and proof of Cyberport cooperation (e.g., MoU, investment letter) where applicable.
  - Personal: Government-issued photo ID, facial photo with ID, and voice/video verification meeting.
- **Storage Requirements**:
  - Minimum of **5 replicas** per dataset.
  - Data stored across **3–4 geographic regions**.
  - Each storage provider (SP) receives no more than **25% of DataCap** per round.
  - Sealing and disclosure nodes must match; discrepancies must be pre-reported.
- **DataCap Distribution** (aligned with HK CyberPort pathway where applicable):
  - Phase 1: 10% of requested amount (or 50% of weekly requested amount for CyberPort clients).
  - Phase 2: 15% (or 100% of weekly requested amount for CyberPort clients).
  - Phase 3: 25%.
  - Phase 4: 50%, with subsequent rounds doubling but capped at **1 PiB per round**.
- **VPN Usage**: Permitted, but clients must ensure actual locations comply with geographic policies; location spoofing is prohibited.
- **Verification Tools**: [DataCapStats.io](https://datacapstats.io) and CID Checker Bot.

## Risk Mitigation Strategies
To protect our organization, reputation, and pathway from abuse, Fivestar implements the following, enhanced by HK CyberPort pathway practices:

- **Operational Security (OpSec)**: KYB/KYC data and client records are stored with encryption and access controls. Regular internal audits prevent data breaches.
- **User Agreements**: Clients sign agreements ensuring compliance with Filecoin Plus policies, geographic requirements, and data ownership responsibilities.
- **Rate Limiting**: DataCap allocation is capped at **1 PiB per client**, with phased distribution (10%–50% or CyberPort’s 50%–100% model) to prevent overuse. Each SP receives no more than **25% per round**.
- **Alerts and Monitoring**: [DataCapStats.io](https://datacapstats.io) and a `check bot` monitor allocation patterns and client activity in real-time, flagging anomalies for manual review.
- **Throttling Mechanisms**: Automated checks limit request frequency and volume to prevent Sybil attacks or spam.
- **Non-Compliance Handling**: Clients have up to **3 weeks** to rectify non-compliance; failure leads to termination of future DataCap allocations.

## Dispute Resolution
Fivestar’s dispute resolution process is fast, transparent, and accountable, incorporating elements from the HK CyberPort pathway:

- **Type 1: Internal Disputes (Client vs. Client)**:
  - **Response Time**: 1–2 days.
  - **Process**: Both parties submit evidence; Fivestar (or Cyberport for pathway clients) determines transparency. We review DataCap records, KYB/KYC compliance, and storage deal details.
  - **Accountability**: Suspend DataCap and resume upon compliance, reclaim unused quotas, or blacklist clients/SPs from future allocations.
- **Type 2: Third-Party Disputes (Against Clients/SPs)**:
  - **Response Time**: 1–2 weeks.
  - **Process**: All parties provide evidence; Fivestar (or Cyberport) facilitates dialogue and determines transparency. Same accountability measures as Type 1.
- **Type 3: Third-Party Disputes (Against Allocator/Pathway)**:
  - **Response Time**: Real-time, supported by Fivestar or Cyberport.
  - **Process**: High transparency is maintained, provided Fivestar’s interests are protected. Evidence is shared with the Fil+ Governance Team.
  - **Accountability**: Suspend pathway access, restore after rectification, or reclaim all unused DataCap quotas.

## Compliance Audit Check
To ensure compliance with program-wide and pathway-specific requirements:

- **Client Compliance**: We verify KYB/KYC documentation, data ownership, and Cyberport cooperation (if applicable) before allocation. Clients confirm adherence to local/regional laws and provide data samples for review.
- **Storage Provider Compliance**: We use [DataCapStats.io](https://datacapstats.io) and CID Checker Bot to verify **5 replicas**, **3–4 geographic regions**, **25% SP allocation limit**, and matching sealing/disclosure nodes. Retrieval rates and redundancy are also checked.
- **Regular Audits**: Internal audits of allocation records, storage deals, and compliance documentation are conducted, with records available for Fil+ Governance Team review.
- **Monitoring Tools**: Continuous monitoring via [DataCapStats.io](https://datacapstats.io) and `check bot` ensures ongoing compliance with program and pathway rules.
