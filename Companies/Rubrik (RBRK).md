# Rubrik (RBRK)

**Category:** Data Security / Cyber Resilience
**Est. Price Per Unit:** ~$100k-$500k+ ARR per enterprise customer (subscription-based)

---

## What They Do

### Product 101 and Where They Fit into the AI Stack

- Rubrik provides a **Zero Trust Data Security** platform that protects enterprise data from cyberattacks, particularly ransomware. While not directly an AI infrastructure company, they sit at a critical intersection: enterprises deploying AI need to protect the proprietary data that makes their models valuable.
- The core offering is **immutable backup** with air-gapped architecture. Unlike traditional backup solutions that can be encrypted alongside production data during ransomware attacks, Rubrik's backups are logically isolated and cannot be modified or deleted by attackers.
- Key platform components:
  - **Rubrik Security Cloud (RSC):** SaaS control plane for managing data protection across hybrid environments (on-prem, cloud, SaaS applications).
  - **Rubrik Cloud Data Management:** The original on-prem appliance product, now integrated into RSC.
  - **Data Threat Analytics:** Uses ML to detect anomalies, identify sensitive data exposure, and provide early warning of ransomware encryption patterns.
  - **Cyber Recovery:** Orchestrated recovery workflows that ensure clean restoration without re-infection.

### Alignment with Overall Thesis
- As enterprises accumulate proprietary datasets for AI training and RAG systems, **data becomes the moat**. Rubrik protects that moat.
- Ransomware attacks increasingly target backup infrastructure first. Organizations running AI workloads on valuable data cannot afford extended downtime—Rubrik's rapid recovery SLAs (hours vs. weeks) are increasingly critical.
- Compliance and data governance requirements for AI (knowing where sensitive data lives, who accessed it) align with Rubrik's data classification and audit capabilities.

### Business Model, Customers
- **Subscription ARR model** with ~90% recurring revenue. Land-and-expand motion as customers protect more workloads over time.
- Pricing based on data under management. Typical enterprise deal is $100k-$500k+ ARR, with large enterprises reaching $1M+.
- Customer base skews toward **regulated industries** (financial services, healthcare, government) and large enterprises with complex hybrid environments.
- Net revenue retention historically 120%+, indicating strong expansion within existing accounts.
- Key competitors: Cohesity (closest architectural comparison), Veeam (volume market), Commvault (legacy incumbent), and cloud-native offerings from AWS/Azure.

### Comments on Team
- **Founder-led.** Bipul Sinha (CEO) co-founded Rubrik in 2014. Previously a partner at Lightspeed Venture Partners with enterprise software investing background.
- Co-founders include Arvind Jain (formerly at Google, built Google Drive infrastructure) and Soham Mazumdar (formerly at Facebook, built data infrastructure).
- Technical DNA from hyperscalers gives credibility in building distributed systems at scale.

### Early View of Moat Hypothesis
- **Architecture:** Immutable, append-only file system is difficult to replicate without ground-up rebuild.
- **Scale data:** Metadata from protecting exabytes of enterprise data feeds ML models for threat detection—network effects in security intelligence.
- **Switching costs:** Once backup infrastructure is embedded, migration is painful (requires re-indexing entire data estate).
- **Trust:** In security, reputation and track record matter. Rubrik has never had a public breach of their backup infrastructure.

---

## Why They're Interesting, and Why Now

- **Ransomware epidemic is structural, not cyclical.** Attack frequency continues to increase, and attackers now specifically target backup systems. This isn't a temporary fear trade.
- **Cyber insurance requirements** are tightening. Insurers increasingly require proven backup/recovery capabilities, making Rubrik a compliance necessity rather than discretionary spend.
- **Cloud transition creates greenfield opportunity.** As enterprises move workloads to multi-cloud, legacy backup tools (Commvault, Veritas) struggle. Rubrik's cloud-native architecture wins in hybrid environments.
- **AI data protection is nascent.** As companies build proprietary AI systems, protecting training data, model weights, and inference pipelines becomes critical. Rubrik is well-positioned to extend into this adjacent market.

---

## Value Creation and Value Capture

### Value Creation
- **Downtime avoidance:** Ransomware recovery without Rubrik can take weeks; with Rubrik, hours. For a large enterprise, each day of downtime can cost $1-10M+.
- **Ransom payment avoidance:** Organizations with reliable backup recovery are far less likely to pay ransoms (average ransom now exceeds $1M).
- **Compliance automation:** Manual data classification and audit preparation costs enterprises significant FTE time; Rubrik automates this.
- **Insurance premium reduction:** Demonstrable cyber resilience capabilities can reduce cyber insurance premiums.

### Value Capture
- Rubrik captures a fraction of the downtime/ransom cost avoided. A $500k ARR contract protecting against potential $10M+ incidents represents strong ROI for customers.
- The challenge is that value is probabilistic—customers pay annually but only realize value during an attack. This creates some sales friction in "peacetime."
- Pricing power exists because switching costs are high and the cost of failure (successful ransomware attack) is catastrophic. Customers don't optimize for cheapest backup solution.
- Expansion revenue comes from protecting additional workloads (SaaS apps, cloud environments) and upselling security analytics features.

---

## Key Risks

- **Hyperscaler competition:** AWS Backup, Azure Backup are "good enough" for some workloads and bundled into cloud spend. Risk that cloud-native backup improves and reduces Rubrik's hybrid advantage.
- **Cohesity merger/consolidation:** The Cohesity-Veritas merger creates a larger competitor with broader enterprise relationships.
- **Commoditization:** If immutable backup becomes table stakes across all vendors, Rubrik's differentiation narrows to execution and ecosystem breadth.
- **Valuation:** Trading at high revenue multiples; needs to sustain 25%+ growth to justify premium.

---

## Gaps in Understanding / Key Questions

- How defensible is the ML-based threat detection? Could established security vendors (CrowdStrike, Palo Alto) add backup as a feature?
- Depth of Microsoft 365 and SaaS backup penetration vs. pure-play competitors like Veeam.
- Unit economics on smaller customers—is there a viable mid-market motion or purely enterprise?
- How does AI data protection differ from traditional workload protection, and what product changes are needed?

---

## Select Financial Graphs

### R1: Total Revenue & YoY Growth
![[Metrics-images/RBRK-R1-Total-Revenue-YoY-Growth.png]]

### R3: LTM Revenue Growth
![[Metrics-images/RBRK-R3-LTM-Revenue-Growth.png]]

### S1: Revenue by Type
![[Metrics-images/RBRK-S1-Revenue-by-Type.png]]

### SUB4: Total RPO & YoY Growth
![[Metrics-images/RBRK-SUB4-Total-RPO-YoY-Growth.png]]

### P4: Non-GAAP EBIT Margin
![[Metrics-images/RBRK-P4-Non-GAAP-EBIT-Margin.png]]

### CF3: LTM Free Cash Flow
![[Metrics-images/RBRK-CF3-LTM-Free-Cash-Flow.png]]

---

## Interesting Topics to Read
- Zero Trust Data Security architecture
- Ransomware attack patterns and backup targeting
- Cyber insurance underwriting requirements
- Cohesity vs. Rubrik competitive positioning
- Cloud-native backup vs. legacy backup vendors
- Data classification for AI compliance
