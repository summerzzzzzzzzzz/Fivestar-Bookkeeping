# Allocator Bookkeeping Repository for Fivestar

## Allocator JSON Link
[Link to Fivestar Allocator JSON](https://github.com/filecoin-project/Allocator-Registry/tree/main/Allocators/Fivestar)  
*Note: Replace with the actual link to your allocator JSON once available in the Allocator-Registry.*

## Client Diligence
Fivestar employs a robust client diligence process to verify clients and establish trust while mitigating Sybil attacks, aligned with the Enterprise-Data-Pathway:

- **New User Check**: 
  - Verify if the GitHub ID is new (<2 months old) or has previously applied for DataCap in this or other pathways. New or first-time applicants are limited to a maximum DataCap allocation (see allocation schedule below).
  - Cross-reference client information with public records and use [DataCapStats.io](https://datacapstats.io) to monitor for suspicious activity.
- **Client ID Check (KYC)**: Applicants complete a free KYC check via Gitcoin Passport, requiring a minimum score of 20 to confirm identity. No personally identifiable information is collected by Fivestar.
- **Client Business Check (KYB)**: 
  - Business clients must complete a KYB check to confirm legitimacy and dataset ownership. Options include:
    1. Third-party KYB service with Synaps.io .
    2. Virtual meeting with the client (lead SP), data owner, and Fivestar team to review dataset ownership (proof of employment, employer signoff, business license) and confirm storage contracts with SPs. Non-disclosure agreements are used to protect client privacy.
- **Storage Provider (SP) Usage Check**: 
  - Clients may use SPs from a vetted SP Marketplace tool (link TBD) or approved network tools (e.g., SPADE). If selecting non-vetted SPs, clients must provide additional KYB information for SPs (e.g., business license, datacenter address proof).
- **Audit Evidence**: All KYC/KYB documentation, allocation records, and communication logs are archived and made available to the Filecoin Plus (Fil+) Governance Team for auditing.

## Description of Data Diligence
Fivestar ensures client data aligns with Filecoin Plus program scope and legal requirements, incorporating best practices from the Enterprise-Data-Pathway:

- **Data Ownership Verification**: Clients provide legal contracts, IP documentation, or signed attestations to prove ownership of private/encrypted datasets. For public datasets, open-access status is verified via public repositories or trusted sources.
- **Legal Compliance**: Clients confirm adherence to local and regional regulations, with data distributed across **3–4 geographic regions** to meet jurisdictional diversity. SP geographic distribution is verified.
- **Data Sampling**: Random sampling is conducted during storage operations using the CID Checker Bot to ensure data in deals matches client claims. [DataCapStats.io](https://datacapstats.io) monitors deal integrity and compliance.
- **Retrieval Standards**: Clients set retrieval standards upfront. If retrieval is required, SPs must maintain an unsealed copy for regular verification (manual or automated) throughout the DataCap allocation period.
- **Tools Used**: [DataCapStats.io](https://datacapstats.io) for allocation tracking, CID Checker Bot for content verification, and AC Bot for weekly compliance checks.
- **Audit Proof**: Logs of data sampling, compliance checks, storage deal metadata, and retrieval verification are maintained for Fil+ Governance Team audits.

## Short Description of Pathway for Clients
Choose Fivestar for a transparent, secure, and enterprise-focused DataCap allocation process, aligned with the Enterprise-Data-Pathway. We serve small-scale developers, enterprise data clients, and Web3 startups, with a focus on private/encrypted datasets and public datasets for non-profit and social impact initiatives. Our rigorous KYC/KYB, virtual meeting options, and phased allocation (up to 5 PiB for trusted users) ensure trust and compliance. With tools like [DataCapStats.io](https://datacapstats.io) and a robust dispute resolution process, we prioritize accountability and secure storage across diverse regions.

## Contact Info
- **Slack**: Join our Slack channel at `#luster` for direct support.
- **Email**: Contact us at [852711390@qq.com](mailto:852711390@qq.com).
- **GitHub Issues**: Open an issue on our [GitHub repository](https://github.com/summerzzzzzzzzzz) for inquiries or support, or apply for DataCap at [Fivestar’s Enterprise-Data-Pathway repo](https://github.com/summerzzzzzzzzzz/Enterprise-Data-Pathway/issues/new).

## Detailed Allocator Policies, Procedures, and Requirements
- **Target Clients**: Small-scale developers, enterprise data clients, individuals learning about Filecoin, and clients onboarding private/encrypted datasets via the Enterprise-Data-Pathway.
- **Supported Data Types**: Public open datasets (research/non-profit), public commercial/enterprise data, private commercial/enterprise data, and private non-profit/social impact data.
- **KYB/KYC Requirements**:
  - Business: Registration certificates, incorporation details, government-issued business IDs, authorized signer verification, and (if applicable) proof of dataset ownership via Synaps.io or virtual meeting.
  - Personal: Gitcoin Passport KYC (minimum score of 20) and virtual meeting for identity confirmation.
- **Storage Requirements**:
  - Minimum of **5 replicas** per dataset (stricter than the pathway’s 2-copy minimum for consistency with Fivestar policy).
  - Data stored across **3–4 geographic regions**.
  - Each storage provider (SP) receives no more than **25% of DataCap** per round.
  - Clients disclose SP partners upfront or use approved network tools (e.g., SP Marketplace, SPADE).
- **DataCap Distribution**:
  - **First-Time User Allocation**:
    - With KYC: Up to **50 TiB**.
    - Without KYC: Up to **10 TiB**.
  - **Trusted User Allocation** (after successful onboarding or for trusted GitHub IDs with prior public dataset experience pre-2024):
    - 1st allocation: 5%
    - 2nd allocation: 15%
    - 3rd allocation: 30%
    - 4th allocation: 50%
    - Eligible for up to **5 PiB** after successful onboarding, with KYC completion.
  - **Subsequent Allocations**: Triggered when >75% of prior DataCap is used, reviewed within a 3-day SLA. Allocations expire after **3 months** if unused.
  - **Non-Compliance**: Applications closed if clients abandon or fail to complete onboarding; GitHub IDs and miner IDs may be flagged for future exclusion.
  - **Alternative Schedule** (for non-pathway clients): Phase 1: 10%, Phase 2: 15%, Phase 3: 25%, Phase 4: 50%, capped at **1 PiB per round**.
- **VPN Usage**: Permitted, but clients must ensure actual locations comply with geographic policies; location spoofing is prohibited.
- **Verification Tools**: [DataCapStats.io](https://datacapstats.io), CID Checker Bot, and AC Bot (weekly compliance checks).

## Risk Mitigation Strategies
To protect our organization, reputation, and pathway from abuse, Fivestar implements the following, enhanced by Enterprise-Data-Pathway practices:

- **Operational Security (OpSec)**: KYC/KYB data and client records are stored with encryption and access controls. Non-disclosure agreements protect client privacy during virtual meetings. Regular internal audits prevent data breaches.
- **User Agreements**: Clients sign agreements ensuring compliance with Filecoin Plus policies, geographic requirements, and data ownership responsibilities.
- **Rate Limiting**: DataCap capped at **1 PiB per round** (or 5 PiB for trusted users), with phased distribution (5%–50%) and a **25% SP allocation limit** per round to prevent overuse.
- **Alerts and Monitoring**: [DataCapStats.io](https://datacapstats.io) and AC Bot monitor deal-making, distribution, and retrieval compliance weekly. CID Checker Bot flags anomalies for manual review.
- **Throttling Mechanisms**: Automated checks limit request frequency and volume to prevent Sybil attacks or spam.
- **Non-Compliance Handling**: Clients providing fake or misleading information face immediate application closure and potential blacklisting of GitHub IDs/miner IDs. Clients have up to **3 weeks** to rectify non-compliance; failure leads to termination of future DataCap allocations.

## Dispute Resolution
Fivestar’s dispute resolution process is fast, transparent, and accountable, aligned with the Enterprise-Data-Pathway:

- **Client Appeals (Allocator vs. Client)**:
  - **Response Time**: 14-day SLA.
  - **Process**: Appeals are submitted via the [Open Data Allocator Appeals Form](https://docs.google.com/forms/d/e/1FAIpQLSfkdb_p9sg5sx_bnSlX0r9rdKXFGmz4dGC1cBtMEYuDym3Ecw/viewform). The Fivestar team reviews evidence privately to respect client confidentiality.
  - **Accountability**: Suspend DataCap, resume upon compliance, reclaim unused quotas, or blacklist clients/SPs from future allocations.
- **Community Disputes (Non-Clients vs. Allocator)**:
  - **Response Time**: 21-day SLA.
  - **Process**: Disputes are addressed via the Filecoin Foundation’s public dispute tracker, with evidence shared transparently while protecting Fivestar’s interests.
  - **Accountability**: Suspend pathway access, restore after rectification, or reclaim all unused DataCap quotas.

## Compliance Audit Check
To ensure compliance with program-wide and pathway-specific requirements:

- **Client Compliance**: KYC via Gitcoin Passport and KYB via Synaps.io or virtual meetings verify client identity and data ownership. Clients confirm adherence to local/regional laws and submit dataset details via [Fivestar’s Enterprise-Data-Pathway repo](https://github.com/summerzzzzzzzzzz/Enterprise-Data-Pathway/issues/new).
- **Storage Provider Compliance**: AC Bot and [DataCapStats.io](https://datacapstats.io) verify **5 replicas**, **3–4 geographic regions**, **25% SP allocation limit**, and SP KYB (if non-vetted SPs are used). Retrieval standards are checked via manual/automated verification.
- **Regular Audits**: Internal audits of allocation records, storage deals, and compliance documentation are conducted, with records available for Fil+ Governance Team review.
- **Monitoring Tools**: Weekly AC Bot checks, [DataCapStats.io](https://datacapstats.io), and CID Checker Bot ensure ongoing compliance. Non-compliant applications are automatically closed if thresholds are not met.
