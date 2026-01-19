# Pure Storage (PSTG)

**Category:** Storage
**Est. Price Per Unit:** ~$150k+ per FlashBlade

---

## What They Do

### Product 101 and Where They Fit into the AI Stack
![[Images/pstg-blades.jpg|300]]

- Pure is often mispriced as a commodity hardware vendor. The thesis is that it's actually a software company wrapping proprietary hardware to solve two constraints in the AI era: power and predictability.
- The key differentiator is **DirectFlash**. Competitors (NetApp, Dell) buy pre-packaged SSDs from Samsung/Hynix with their own internal controllers doing garbage collection and wear leveling independently. Pure buys raw NAND chips and manages them via software-defined controllers at the system level.
- This architecture has three implications:
  - Power/density: removing individual controllers reduces power/TB by ~50%. They ship 75TB modules with a roadmap to 300TB.
  - QLC economics: Pure can use lower-cost, lower-endurance **QLC NAND** but achieve TLC-level reliability because their software manages writes globally, preventing uneven wear.
  - Deterministic latency: no random latency spikes from SSDs doing their own maintenance. Critical for keeping GPUs fed without tail latency stalls.

### Alignment with Overall Thesis
- As LLM context windows grow (1M+ tokens), GPU HBM is too expensive to store the full KV cache. Pure allows offload to local flash with low enough latency to prevent stalls—effectively RAM expansion for inference.
- In training clusters, if one storage node hangs, the entire GPU cluster waits. Deterministic latency maximizes GPU utilization.
- For RAG architectures in finance/gov, indexing proprietary data on-prem avoids cloud egress fees and regulatory risk.

### Business Model, Customers
- ~$150k+ per blade. Data gravity purchasing dynamic—bought when data buckets fill up.
- **Evergreen subscription** model: unlike competitors requiring forklift upgrades every 3-5 years, Pure upgrades controllers non-disruptively. This locks in customers and improves margins over time.
- Pure isn't trying to beat AWS/Azure at general cloud storage. They're the premium tier for difficult workloads.
- Meta's AI Research SuperCluster uses Pure. Google Distributed Cloud (reportedly Google's fastest-growing division) uses Pure as the physical storage layer.
- RPO growth (24%) is outpacing revenue growth (17%)—signals a backlog of large commitments.
- Acquired **Portworx**, the leading Kubernetes data layer. Gives Pure a software hook into applications, not just hardware.
- Competitive context: NetApp is software-on-commodity (bound by Samsung/Kioxia physics). Hyperscaler native storage is "good enough" but IOPS/$ is poor. DIY NAND is theoretically possible but building an enterprise-grade flash translation layer took Pure 10+ years.

### Comments on Team
- Founded in 2009.
- Founder is now Chief Visionary Officer and Director.
- Other co-founder is an advisor.

### Early View of Moat Hypothesis
- 10+ years of flash translation layer IP. Building an FTL that handles QLC reliability at enterprise level is non-trivial.
- Evergreen subscription creates switching costs.
- Portworx creates application-level stickiness beyond hardware.

---

## Why They're Interesting, and Why Now
- The thesis shifts from "storage for databases" to "storage for AI context." We have to believe AI inference moves on-prem and hybrid—if that plays out, Pure becomes a hyperscaler partner rather than competitor.
- 1M+ token LLMs need KV cache offload. Pure's low-latency flash could serve as HBM expansion, though this use case is still emerging.
- Data center power is the new bottleneck. Pure's 50% power/TB advantage is tangible and measurable.

### Enterprise AI Storage: Qualitative Signals

Enterprises are starting to think about storage more strategically for AI workloads. This is a shift from storage as commodity infrastructure to storage as a performance-critical component of the AI stack.

![[Slides/4-QualitateData_PSTG.png]]

---

## Key Risks
- If standard SSD controllers improve enough to handle QLC reliably, Pure's margin advantage erodes.
- If AI inference moves entirely to memory-heavy chips (Groq, Cerebras) that don't need storage offload, the AI tailwind weakens.
- Customer concentration—heavy reliance on Meta and potentially 1-2 others creates binary risk.

---

## Gaps in Understanding / Key Questions
- How defensible is FTL IP if Samsung/Kioxia invest heavily in controller software?
- Depth of Meta relationship—is Pure truly tool of record or one of several vendors?
- Portworx adoption—is Kubernetes storage actually sticky or commoditizing?

---

## Select Financial Graphs

### R1: Total Revenue & YoY Growth
![[Metrics-images/PSTG-R1-Total-Revenue-YoY-Growth.png]]

### R3: LTM Revenue Growth (Total, Product, Support)
![[Metrics-images/PSTG-R3-LTM-Revenue-Growth-Total-Product-Support-.png]]

### I1: Inventory Turns
![[Metrics-images/PSTG-I1-Inventory-Turns.png]]

### SUB2: Total RPO & YoY Growth
![[Metrics-images/PSTG-SUB2-Total-RPO-YoY-Growth.png]]

### SUB3: RPO vs Revenue vs Support Growth
![[Metrics-images/PSTG-SUB3-RPO-vs-Revenue-vs-Support-Growth.png]]

### V1: EV/Sales NTM
![[Metrics-images/PSTG-V1-EV-Sales-NTM.png]]

---

## Interesting Topics to Read
- DirectFlash vs. commodity SSD architecture
- QLC vs. TLC NAND economics and reliability
- KV Cache offload for large context LLMs
- Pure Evergreen subscription model
- Portworx and Kubernetes storage
- NetApp competitive positioning
