# Camtek (CAMT)

**Category:** Inspection
**Est. Price Per Unit:** ~$800k - $1M per system

---

## What They Do

### Product 101 and Where They Fit into the AI Stack
![[Images/camt-machine.png|300]]

- Camtek designs and builds **optical inspection and metrology systems** that sit at the mid-end and back-end of the fab. They inspect wafers after transistors are made but before or during packaging—the quality control checkpoint between chip fabrication and final assembly.
- Their **Eagle** systems do 100% bump inspection for HBM. High Bandwidth Memory stacks 8-12 layers of DRAM vertically, connected by thousands of microscopic through-silicon vias (TSVs) and micro-bumps. If a single bump is defective on layer 4, the entire stack is ruined. Camtek catches these before bonding.
- The **Hawk** system is the newer bet. As the industry moves from micro-bumps to **hybrid bonding** (copper-to-copper without bumps), you need 3D nanometer-level flatness measurement, not just 2D inspection. Camtek acquired FRT Metrology (German sensor tech) to build this capability.
- They're also positioning for **glass core substrates** (next-gen packaging for Intel/AMD AI chips) and inspect 200+ layer 3D NAND stacks for enterprise SSDs.

### Alignment with Overall Thesis
- An H100 GPU or HBM stack costs thousands of dollars. A Camtek machine costs under $1M. The math on yield protection is obvious—these are no-regrets purchases.
- The shift to chiplets means more connections per package. More connections = more points of failure = more need for inspection. Camtek benefits from complexity, not just volume.
- HBM4 (2025/26) increases connection density and may require hybrid bonding, which should drive Hawk upgrades.

### Business Model, Customers
- Primarily CAPEX-driven hardware sales. ~20-25% recurring from service contracts, spare parts, and software on an installed base of ~3,000 systems.
- Camtek is the tool of record at major OSATs (ASE, Amkor) and has secured tool of record status for HBM inspection at tier-1 memory makers (implies SK Hynix, Samsung, Micron).
- Unlike KLA (which targets front-end fabs), Camtek dominates the assembly houses.
- "Double dip" economics: if TSMC keeps packaging in-house, Camtek sells to TSMC. If TSMC hands off to Amkor (as in Arizona), Camtek sells to Amkor.

### Comments on Team
- Founder led, Israeli (founded 1987).
- Co-founder Rafi Amit is CEO and previously CTO.
- Known for aggressive moat protection—the FRT acquisition was partly to block competitors from entering via hybrid bonding.

### Early View of Moat Hypothesis
- KLA and Onto offer higher precision but are slower and more expensive. Camtek's sweet spot is high-speed 100% inspection that doesn't bottleneck the line. In high-volume packaging, speed matters more than atomic-level precision.
- 3,000+ machines in the field. Displacing Camtek requires retraining operators and rewriting inspection recipes. Switching costs are high for low-margin OSATs.
- The FRT acquisition blocked competitors from using hybrid bonding as an entry point.

---

## Why They're Interesting, and Why Now
- Pick-and-shovel play on advanced packaging. As transistor scaling slows, performance gains come from stacking chips vertically. Camtek provides the inspection layer. We have to believe packaging complexity keeps growing.
- HBM4 cycle (2025/26) should drive Hawk upgrades, though timing is uncertain.
- Glass substrates give optionality but are speculative.

---

## Key Risks
- CAPEX-driven model is cyclical.
- KLA could push deeper into back-end/packaging inspection.
- If hybrid bonding adoption is slower than expected, Hawk uptake disappoints.
- Customer concentration in HBM memory makers and large OSATs.

---

## Gaps in Understanding / Key Questions
- How differentiated is Hawk vs. KLA/Onto for hybrid bonding? Does the speed vs. precision trade-off hold at nanometer scale?
- What portion of revenue is truly AI-driven vs. traditional packaging?
- Has FRT/SurfaceSens technology been fully productized?

---

## Select Financial Graphs

### R1: Total Revenue & YoY Growth
![[Metrics-images/CAMT-R1-Total-Revenue-YoY-Growth.png]]

### I1: Inventory Turns
![[Metrics-images/CAMT-I1-Inventory-Turns.png]]

### P4: Operating Margin
![[Metrics-images/CAMT-P4-Operating-Margin.png]]

### V1: EV/Sales NTM
![[Metrics-images/CAMT-V1-EV-Sales-NTM.png]]

---

## Interesting Topics to Read
- Back end semiconductor testing
- Camtek vs. ONTO vs. KLA positioning
- Hybrid Bonding vs. micro-bump inspection requirements
- HBM4 packaging architecture
- Glass Core Substrates for AI chips
- Through-Silicon Via (TSV) technology
