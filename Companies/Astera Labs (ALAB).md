# Astera Labs (ALAB)

**Category:** Fabless Components
**Est. Price Per Unit:** ~$50 per Aries chip, ~$300 per Leo CXL chip

---

## What They Do

### Product 101 and Where They Fit into the AI Stack
![[Images/alab-retimers.jpg|300]]

- ALAB's primary revenue source is **retimers (80%+)**. These are physical devices that 'boost and clean' electrical signals that are sent over copper. Without these retimers, copper signals become too noisy and the '1s and 0s' are interpreted correctly and the system fails. Retimers are a critical component of all motherboards - every AI chip has several retimers. 
- Common retimers, like the ones in your laptop are fairly undifferentiated, but advanced systems use newer protocols (e.g., **PCIe Gen6**) which double the bandwidth and increase error rates without advanced retimers.
- **ALAB's Scorpio switches** are also growing quickly. These coordinate the communication leaving the GPU (Nvswitch is for GPU-GPU, and PCIe switches direct traffic outside the GPU, and Retimers boost that traffic).
- ALAB is also a pioneer in **CXL technology** (unproven, but testing), which is a protocol to connect memory over copper to create a unified memory pool. As memory requirements increase, pooling memory may become more critical, at least for spillover, and Astera Labs chips become more important.
- Lastly, ALAB has a management software called **COSMOS**, which is becoming increasingly important. It provides basic observability of traffic signals that help engineers diagnose faulty equipment. The cost and value of equipment is increasing, so utilisation becomes far more valuable. For example, COSMOS can help detect an elevated bit error rate in a cable so it can be replaced. COSMOS also enables firmware updates for fleet management, allowing data centre engineers to optimise traffic.

### Alignment with Overall Thesis
- Bottlenecks and downtime become more expensive, so leading retimers with higher bandwidth and better diagnostics become increasingly valuable, increasing the value of prop leading retimers.
- As memory becomes more of a bottleneck, fast SSD storage may become more critical for large scale systems or local enterprise fine tuning; if this plays out, CXL chips could help enable this transition.

### Business Model, Customers
- ALAB revenue is from selling units, e.g., to Nvidia, and then TSMC or an ODM such as Foxconn packages them.
- **Reference designs are important** for ALAB; for example, if Nvidia requires ALAB retimers for their unit, then manufacturers (e.g., Dell) are required to purchase them.
- ALAB has a **highly concentrated customer base**: 27% of revenue comes from the largest customer, and 84% of revenue comes from major customers.
- Est. $50 per chip for Aries, $300 per chip for Leo CXL. An H100 uses 8-16 Aries chips.

### Comments on Team
- **Founder led.** Three co-founders left Texas Instruments to found ALAB in 2017.
- The three co-founders are key executives (CEO, COO, CPO). They appear more product oriented vs. the typical research veteran team.
- They are more focused on practical implementation. Their **Cloud Scale Interop Lab** research centre is used to stress test communication with components as an important pre-validation phase.

### Early View of Moat Hypothesis
- Leading position for a critical component.
- COSMOS software to differentiate vs. other providers.
- Deep process experience in practical stress tests.

---

## Why They're Interesting, and Why Now
- Communication bottlenecks are becoming increasingly costly as the demand for both larger context and lower latency increases. GPU-GPU communication is outside the scope of ALAB, but every inference call must communicate externally either with a NIC or a CPU. Even with Nvidia's CPU-GPU packaging, external communication is required, and currently, at least some of this is done via copper.
- Astera Labs is a **leader in high frequency copper communication**, which becomes more difficult with higher bandwidth (e.g., PCIe6).
- Given that copper is currently in a shortage, one can assume that recent demand has increased.
- We need to believe that the AI buildout continues, and that ALAB will be attached to an increasing portion of an increasing volume of chips.

---

## Key Risks and Gaps
- How quickly the industry moves to **co-packaged optics** and how that influences retimer requirements
  - ALAB has a newer photonics research lab and acquired a photonics company for optical interconnects.
- CXL impact appears to be largely theoretical at this point and may not become standard.

---

## Select Financial Graphs

### R2: LTM Revenue
![[Metrics-images/ALAB-R2-LTM-Revenue.png]]

### I1: Inventory Turns
![[Metrics-images/ALAB-I1-Inventory-Turns.png]]

### S2: Geographic Revenue Mix
![[Metrics-images/ALAB-S2-Geographic-Revenue-Mix-.png]]

### V1: EV/Sales NTM
![[Metrics-images/ALAB-V1-EV-Sales-NTM.png]]

---

## Interesting Topics to Read
- Retimers and PCIe Gen6
- CXL (Compute Express Link)
- Grace Hopper combined CPU and GPU packaging
