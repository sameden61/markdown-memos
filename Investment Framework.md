# Investment Framework: AI Infrastructure Thesis

This document presents several frameworks for categorizing the investment universe. Each framework highlights different dimensions of the thesis. Choose the one(s) that best communicate your thinking.

---

## Framework 1: The Complexity Tax Matrix

**Core Insight:** As AI chips become more complex, certain companies extract a "complexity tax"—they capture more value per unit as complexity increases, rather than just scaling with volume.

```
                    VALUE CAPTURE MECHANISM

           Volume-Linked              Complexity-Linked
           (More chips = more $)      (Harder chips = more $/chip)
         ┌─────────────────────────┬─────────────────────────┐
    H    │                         │                         │
    I    │      MICRON             │     TECHNOPROBE         │
    G    │      (HBM stacks)       │     (AI probe cards     │
    H    │                         │      cost 2x+ more)     │
         │      ASTERA LABS        │                         │
    A    │      (retimers/chip)    │     CAMTEK              │
    I    │                         │     (100% inspection    │
         │                         │      for chiplets)      │
    E    │                         │                         │
    X    │                         │     BE SEMI             │
    P    │                         │     (hybrid bonding     │
    O    │                         │      monopoly bet)      │
    S    ├─────────────────────────┼─────────────────────────┤
    U    │                         │                         │
    R    │      PURE STORAGE       │     FORMFACTOR          │
    E    │      (data growth)      │     (HBM testing        │
         │                         │      complexity)        │
    L    │      RUBRIK             │                         │
    O    │      (attack surface    │     LAM RESEARCH        │
    W    │       growth)           │     (200+ layer NAND)   │
         │                         │                         │
         │                         │     KLA                 │
         │                         │     (yield = critical)  │
         └─────────────────────────┴─────────────────────────┘
```

**Why this matters:** Volume-linked plays are more cyclical and commoditized over time. Complexity-linked plays have natural ASP expansion as the industry advances.

---

## Framework 2: Revenue Model x Moat Durability

**Core Insight:** The best businesses combine recurring/consumable revenue with strong technical moats. Capex businesses need stronger moats to justify cyclicality.

```
                         MOAT DURABILITY

              Process Know-How        Monopoly/Standard
              (Years of learning)     (No alternative exists)
         ┌─────────────────────────┬─────────────────────────┐
         │                         │                         │
    R    │  ★ TECHNOPROBE          │                         │
    E    │    (vertical probe IP)  │                         │
    C    │                         │                         │
    U    │  ★ FORMFACTOR           │  ★ ASTERA LABS          │
    R    │    (MEMS parallelism)   │    (PCIe reference      │
    R    │                         │     designs)            │
    I    │  ★ PURE STORAGE         │                         │
    N    │    (DirectFlash FTL)    │  ★ RUBRIK               │
    G    │                         │    (immutable backup    │
         │                         │     architecture)       │
         ├─────────────────────────┼─────────────────────────┤
         │                         │                         │
    C    │    CAMTEK               │    ASML                 │
    A    │    (speed/precision     │    (EUV monopoly)       │
    P    │     balance)            │                         │
    E    │                         │    BE SEMI              │
    X    │    LAM RESEARCH         │    (hybrid bonding      │
         │    (HAR etch)           │     leader)             │
         │                         │                         │
         │    KLA                  │    MICRON               │
         │    (algorithms +        │    (1 of 3 HBM          │
         │     installed base)     │     suppliers)          │
         └─────────────────────────┴─────────────────────────┘

★ = Sweet spot (recurring + defensible)
```

**Investment implication:** Recurring revenue businesses (top row) can justify higher multiples because earnings are more predictable. Capex businesses (bottom row) need to be bought at cycle troughs.

---

## Framework 3: The Value Chain "Toll Booth" Map

**Core Insight:** Different companies extract value at different points in the chip lifecycle. Understanding position reveals exposure and pricing power.

```
CHIP LIFECYCLE STAGE:

DESIGN    FABRICATION         PACKAGING/TEST         DEPLOYMENT
  │            │                    │                     │
  │     ┌──────┴──────┐      ┌──────┴──────┐      ┌──────┴──────┐
  │     │             │      │             │      │             │
  │     │   ASML      │      │  BE SEMI    │      │ PURE STORAGE│
  │     │   (litho)   │      │  (bonding)  │      │ (inference  │
  │     │             │      │             │      │  storage)   │
  │     │   LAM       │      │  CAMTEK     │      │             │
  │     │   (etch)    │      │  (inspect)  │      │ RUBRIK      │
  │     │             │      │             │      │ (data       │
  │     │   KLA       │      │ TECHNOPROBE │      │  protection)│
  │     │   (inspect) │      │  (test)     │      │             │
  │     │             │      │             │      │ ASTERA LABS │
  │     │             │      │ FORMFACTOR  │      │ (interconn) │
  │     │             │      │  (test)     │      │             │
  │     │   MICRON    │      │             │      │             │
  │     │   (memory   │      │             │      │             │
  │     │    IDM)     │      │             │      │             │
  │     └─────────────┘      └─────────────┘      └─────────────┘
  │
  │     $150M-380M/tool      $50k-2M/unit         $100k-500k ARR
  │     (capex)              (consumable/capex)   (subscription)
```

**Key insight:** The further right on the value chain, the closer to recurring revenue and end-customer relationships. The further left, the more capex-driven and cyclical.

---

## Framework 4: The "Sweet Spot" Scorecard

**Core Insight:** Your thesis appears to favor specific characteristics. This scorecard makes the criteria explicit.

| Company | Founder-Led | Market Cap | Revenue Model | AI Leverage | Complexity Premium | Total |
|---------|-------------|------------|---------------|-------------|-------------------|-------|
| **TECHNOPROBE** | ✓✓ (Family) | Mid | Consumable | Direct | High | **9/10** |
| **CAMTEK** | ✓✓ (Founder CEO) | Small | Capex+ | Direct | High | **8/10** |
| **BE SEMI** | ✓✓ (Founder CEO) | Mid | Capex | Architecture bet | Extreme | **8/10** |
| **ASTERA LABS** | ✓✓ (Founder team) | Mid | Component | Direct | Medium | **8/10** |
| **PURE STORAGE** | ✓ (Founder involved) | Mid | Subscription | Indirect | Medium | **7/10** |
| **RUBRIK** | ✓✓ (Founder CEO) | Mid | Subscription | Adjacent | Medium | **7/10** |
| **FORMFACTOR** | ✗ | Small | Consumable | Direct (HBM) | High | **6/10** |
| **MICRON** | ✗ | Large | Product | Direct | Low | **5/10** |
| **KLA** | ✗ | Large | Capex+ | Direct | High | **4/10** |
| **LAM RESEARCH** | ✗ | Large | Capex | Indirect | Medium | **3/10** |
| **ASML** | ✗ | Mega | Capex | Direct | Low | **2/10** |

**Scoring logic:**
- Founder-led: ✓✓ = 2pts, ✓ = 1pt, ✗ = 0pts
- Market cap: Small = 2pts, Mid = 1pt, Large/Mega = 0pts
- Revenue model: Subscription/Consumable = 2pts, Capex+ = 1pt, Pure Capex = 0pts
- AI leverage: Direct = 2pts, Indirect/Adjacent = 1pt
- Complexity premium: Extreme/High = 2pts, Medium = 1pt, Low = 0pts

---

## Framework 5: Value Creation vs. Value Capture Map

**Core Insight:** Not all companies that create value capture it proportionally. This framework separates the two dimensions.

```
                        VALUE CAPTURE
                        (Pricing power, moat, share of economics)

                   Low                              High
              (Commoditizing)                 (Defensible margin)
         ┌─────────────────────────┬─────────────────────────┐
         │                         │                         │
    H    │                         │    ASML                 │
    I    │   MICRON                │    (monopoly, but       │
    G    │   (critical but         │     >$300B mkt cap)     │
    H    │    oligopoly pricing    │                         │
         │    pressure)            │    BE SEMI              │
    V    │                         │    (IF hybrid bonding   │
    A    │                         │     wins = monopoly)    │
    L    │                         │                         │
    U    │                         │    TECHNOPROBE          │
    E    │                         │    (design lock-in,     │
         │                         │     complexity ASP)     │
    C    │                         │                         │
    R    │                         │    CAMTEK               │
    E    │                         │    (tool of record,     │
    A    │                         │     speed moat)         │
    T    │                         │                         │
    I    ├─────────────────────────┼─────────────────────────┤
    O    │                         │                         │
    N    │   LAM RESEARCH          │    PURE STORAGE         │
         │   (essential but        │    (power efficiency    │
    L    │    competitive)         │     + Evergreen lock-in)│
    O    │                         │                         │
    W    │   FORMFACTOR            │    ASTERA LABS          │
         │   (memory cyclical,     │    (reference design    │
         │    share pressure       │     + COSMOS software)  │
         │    from TPRO)           │                         │
         │                         │    RUBRIK               │
         │   KLA                   │    (catastrophic        │
         │   (high capture but     │     downside = sticky)  │
         │    already priced in)   │                         │
         └─────────────────────────┴─────────────────────────┘
```

**Investment thesis:** Target the **upper-right quadrant** (high value creation + high value capture), but be aware that some are already priced for perfection (ASML). The **emerging upper-right** plays (BE Semi if hybrid bonding works, Technoprobe, Camtek) offer better risk/reward.

---

## Framework 6: The Thesis in One Sentence

Each company can be summarized by its core thesis:

| Company | One-Line Thesis |
|---------|-----------------|
| **TECHNOPROBE** | AI chips need 2x the pins = 2x the probe card price |
| **CAMTEK** | Chiplets mean 100% inspection (not sampling) at every connection |
| **BE SEMI** | Hybrid bonding is the next architecture; BESI wins if it happens |
| **ASTERA LABS** | Every signal leaving a GPU needs a retimer; complexity = more retimers |
| **FORMFACTOR** | HBM needs Known Good Die testing before stacking 8+ layers |
| **PURE STORAGE** | AI inference needs low-latency local storage; Pure has 50% power advantage |
| **RUBRIK** | Proprietary AI data is the new moat; Rubrik protects that moat |
| **MICRON** | 1 of 3 HBM suppliers; sold out through 2026 |
| **KLA** | Yield management for $1,000+ chips; too big for alpha, good for context |
| **LAM RESEARCH** | Enables 200+ layer NAND; better expressed via Pure Storage |
| **ASML** | EUV monopoly; priced for perfection, essential for understanding |

---

## Recommended "Killer Slide" Combinations

### Option A: Simple 2x2 (Framework 1)
Use the **Complexity Tax Matrix** if your audience cares about *why* certain businesses structurally outperform. Message: "We invest in companies that charge more as chips get harder, not just as volumes increase."

### Option B: Portfolio Construction View (Framework 4 + 6)
Use the **Sweet Spot Scorecard** + **One-Line Thesis** table for portfolio reviews. Shows explicit criteria and quick thesis recall.

### Option C: Value Chain Story (Framework 3)
Use the **Toll Booth Map** if explaining to someone unfamiliar with semis. Shows where each company sits and why that position matters.

### Option D: Sophisticated Investor View (Framework 5)
Use **Value Creation vs. Value Capture** for sophisticated audiences. Shows you understand that creating value ≠ capturing value, and identifies where alpha exists vs. priced-in.

---

## Appendix: Company Quick Reference

| Ticker | Category | Price Point | Revenue Type | Sweet Spot? |
|--------|----------|-------------|--------------|-------------|
| TPRO | Test (Consumable) | $50-100k/card | Consumable | ✓ |
| FORM | Test (Consumable) | $75-150k/card | Consumable | Partial |
| CAMT | Inspection | $800k-1M/system | Capex+ | ✓ |
| BESI | Equipment | $2M/machine | Capex | ✓ (if HB wins) |
| ALAB | Components | $50-300/chip | Component | ✓ |
| PSTG | Storage | $150k+/blade | Subscription | ✓ |
| RBRK | Data Security | $100-500k ARR | Subscription | ✓ |
| MU | Memory | $300-400/HBM stack | Product | Context |
| KLAC | Inspection | $5-10M/tool | Capex+ | Context |
| LRCX | Equipment | $3-5M/tool | Capex | Context |
| ASML | Equipment | $150-380M/tool | Capex | Context |
