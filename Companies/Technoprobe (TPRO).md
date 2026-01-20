# Technoprobe (TPRO)

**Category:** Test Equipment (Consumable)
**Est. Price Per Unit:** $50k - $100k+ per card (AI cards significantly more expensive)

---

## What They Do

### Product 101 and Where They Fit into the AI Stack
![[Images/tpro-card.jpg|300]]

- Technoprobe manufactures **probe cards**—consumable interfaces required to test chips (CPUs, GPUs, AI accelerators) before they are packaged.
- Before a chip goes into a plastic case and gets soldered into a phone or server, it must be tested. If you package a broken chip, you waste money on packaging and risk shipping a dud. The problem is that silicon wafers have millions of microscopic contact points, and the testing machine (ATE) is too clumsy to touch them directly.
- A probe card is a round circuit board with thousands of microscopic MEMS needles in the center. These needles physically prick the wafer to create an electrical loop for testing.
- Every time Nvidia or Apple designs a new chip, the contact point layout changes. They must buy a new custom probe card.

### Alignment with Overall Thesis
- AI chips are massive and require probe cards with tens of thousands of pins. These cards cost $100k+ vs. standard cards at $50k.
- Chiplets and advanced packaging (CoWoS, SoIC) require **Known Good Die** testing—you can't stack chips without verifying each layer works. One bad layer ruins the whole stack. This drives 100% testing coverage and higher probe card volume.
- Technoprobe specialises in logic (processors), not memory. Directly aligned with AI accelerator growth.

### Business Model, Customers
- $50k-$100k+ per card. AI/advanced logic at the high end.
- Unlike ATE machines (Teradyne), which are one-time capex, probe cards are consumables. Volume driven (more chips = more wear = more replacement) and design driven (new chip = new card).

### Comments on Team
- Family led, Italian. Founded in 1995 by Giuseppe Crippa in a garage. Family still owns controlling stake.
- Co-founder was CEO until 2017 (age 82) and passed in 2025.
- Current CEO is founder's nephew; Chairman and Vice Chairman are founder's sons.
- Engineering-first, secretive, agile. Known for being technically superior in **vertical probe cards** (the type needed for high-end logic). 
### Early View of Moat Hypothesis
- Design lock-in: every new chip needs a new probe card. Once you're the incumbent, switching mid-production is painful.
- Technical leadership in vertical probes—decades of precision engineering investment.
- Family structure allows faster iteration than publicly traded American competitors.

---

## Why They're Interesting, and Why Now
- AI chips are bigger and more complex = more pins, more testing, higher-value cards. We have to believe AI chip production scales—if it does, Technoprobe is a direct beneficiary.
- Chiplets increase the need for Known Good Die testing. You can't stack without verifying.
- Unlike one-time capex equipment, probe cards are consumables that scale with production volume. More recurring dynamics.

---

## Key Risks
- Customer concentration. If one of the Giants shifts to FormFactor, it hurts.
- Tech disruption: if chip designs move to wafer-level burn-in or self-testing architectures, probe card TAM shrinks.
- Family governance can be a strength (long-term thinking) or weakness (succession, capital allocation).

---

## Gaps in Understanding / Key Questions
- How defensible is the technical lead vs. FormFactor? Winning on tech or relationships/price?
- Actual customer concentration breakdown—is it 50% TSMC or more diversified?
- Succession planning—how deep is the bench beyond the Crippa family?

---

## Select Financial Graphs

### R1: Total Revenue & YoY Growth
![[Metrics-images/TPRO-R1-Total-Revenue-YoY-Growth.png]]

### I1: Inventory Turns
![[Metrics-images/TPRO-I1-Inventory-Turns.png]]

### P2: Gross Margin
![[Metrics-images/TPRO-P2-Gross-Margin.png]]

### P4: EBIT Margin
![[Metrics-images/TPRO-P4-EBIT-Margin.png]]

### CF2: FCF Margin
![[Metrics-images/TPRO-CF2-FCF-Margin.png]]

### V1: EV/Sales NTM
![[Metrics-images/TPRO-V1-EV-Sales-NTM.png]]

---

## Interesting Topics to Read
- Probe cards vs. ATE (Teradyne, Advantest)
- Vertical Probe Cards vs. Cantilever technology
- Known Good Die (KGD) testing for chiplets
- FormFactor competitive positioning
- MEMS probe technology
