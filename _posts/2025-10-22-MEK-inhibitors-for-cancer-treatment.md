---
title: "MEK and MAPK Inhibitors — A Detour Around the KRAS Roadblock"
description: "Building on earlier KRAS posts, this dives into MEK/MAPK strategies—with a closer look at Immuneering’s Deep Cyclic Inhibitors—and what it could mean for colon cancer."
date: 2025-10-22
categories: Science

---

In earlier posts, I laid out why **KRAS mutations** have been so stubborn for drug development.  
In [*KRAS, EGFR, and Drugs*](https://jamestsay-12.github.io/blog-site/science/2025/08/06/KRAS-EGFR-and-Drugs.html), I walked through the structural reasons KRAS is hard to drug.  
[*Targeted Colon Cancer Treatment Status*](https://jamestsay-12.github.io/blog-site/science/2025/08/12/Targeted-Colon-Cancer-treatment-status.html) covered how these mutations drive colon cancer and where targeted therapies stand today.  
And in [*Pan-RAS Inhibitors: Mechanism and Efficacy*](https://jamestsay-12.github.io/blog-site/science/2025/08/13/Pan-Ras-Inhibtors-Mechanism-and-Efficacy.html), I looked at efforts to shut down RAS more broadly.

This piece takes a different angle: **don’t fight KRAS head-on—jam its wiring downstream.** That means the **MAPK pathway**, especially **MEK** and **ERK**.

---

## The MAPK pathway: the relay that keeps growth signals moving

![MAPK Pathway](https://github.com/JamesTsay-12/blog-site/blob/main/assets/img/science/MAPKpathway_diagram.svg.png?raw=true)

*Image credit: [Fred the Oyster, Wikipedia](https://en.wikipedia.org/wiki/MAPK/ERK_pathway).*

At a high level: **RAS → RAF → MEK → ERK → transcription**.  
When KRAS is mutated “on,” this relay pushes cells to proliferate and resist death signals. If you can’t hit KRAS cleanly, cutting power further down the chain can still stall the tumor.

---

## Why the first wave of MEK inhibitors struggled

The chemistry worked; the biology pushed back.

- **Feedback reactivation.** Shut off MEK and the cell cranks up **RAF/RTKs/KRAS** upstream to re-ignite ERK.  
- **Resistance mutations.** Tumors evolve **MEK1/2 pocket changes** (e.g., F53L, K57N, Q56P) and sometimes **ERK mutations** downstream that bypass MEK entirely.  
- **Toxicity ceiling.** MAPK signaling matters in normal tissue (skin, retina, GI). Chronic blockade → **rash, diarrhea, fatigue, ocular effects**; doses get trimmed just as tumors start to adapt.

That’s why **trametinib, cobimetinib, binimetinib** had brief single-agent wins and then needed combinations:
**MEK + EGFR**, **MEK + CDK4/6**, **MEK + PI3K**—all attempts to box in escape routes.

---

## Deep Cyclic Inhibitors: a different rhythm (Immuneering)

**Immuneering (IMRX)** rethinks the problem with what they call **Deep Cyclic Inhibitors (DCIs)**. Instead of sitting on MEK 24/7 (and advertising to the cell that something’s wrong), DCIs deliver **high-amplitude pulses** of MEK inhibition—deep enough to collapse ERK signaling—then allow a **brief, controlled release**. Normal cells can recover; KRAS-addicted tumor cells, which need continuous MAPK drive, don’t bounce back as easily.

**Atebimetinib**, their oral once-daily DCI of MEK, is built to **encode that rhythm pharmacokinetically** (not by complicated dosing calendars). The aim: **longer pathway suppression, less feedback rebound, better tolerability.**

> ---
> ### 🧠 Technical Box — Continuous vs. Deep Cyclic MEK inhibition
>
> **Continuous (traditional) MEK inhibition**  
> • Flat exposure; MEK/ERK off constantly  
> • Strong feedback (RAF/RTKs) and fast resistance emergence  
> • Higher steady toxicity in MAPK-dependent tissues
>
> **Deep Cyclic Inhibition (DCI)**  
> • Pulsed, high-amplitude MEK suppression with short troughs  
> • Blunts compensatory loops; maintains downstream suppression longer  
> • “Recovery windows” improve tolerability without losing anti-tumor pressure
>
> Visual sketch:
>
> ![Continuous vs Deep Cyclic](https://github.com/JamesTsay-12/blog-site/blob/main/assets/img/science/deep%20cyclic.png?raw=true)
>
> *Schematic comparison of exposure patterns and expected biology.*
> ---

Early clinical traction is in **pancreatic** and **lung** cancers—two MAPK-addicted settings:
- Immuneering–Lilly clinical supply: https://ir.immuneering.com/news-releases/news-release-details/immuneering-announces-clinical-supply-agreement-lilly-evaluate  
- Pancreatic combo data summary: https://www.targetedonc.com/view/encouraging-survival-safety-data-for-atebimetinib-combo-in-pancreatic-cancer  
- Survival data update: https://ir.immuneering.com/news-releases/news-release-details/immuneering-discuss-recently-announced-overall-survival-data  
- Trial record: [NCT06208124](https://clinicaltrials.gov/study/NCT06208124?term=immuneering&rank=1)

**Colorectal cancer** isn’t on that trial card yet, but the biology overlaps. External analyses peg a non-trivial probability of expansion to mCRC if safety/efficacy hold:
https://www.pharmaceutical-technology.com/data-insights/imm-6-415-immuneering-metastatic-colorectal-cancer-likelihood-of-approval/

---

## Where the rest of the field is

| Class | KRAS coverage | Stage | Examples | What we’ve learned |
|---|---|---|---|---|
| **MEK inhibitors** | All KRAS | Phase 2+ | Trametinib, Binimetinib | Need combos (EGFR, CDK4/6, PI3K) to delay rebound; monotherapy durability limited |
| **ERK inhibitors** | All KRAS | Phase 1/2 | Ulixertinib | One step further downstream; manageable tox so far; still early |
| **Combo logic** | All KRAS | Ongoing | MEK+EGFR, MEK+CDK4/6, MEK+PI3K | Best for cutting off feedback and cell-cycle escape; tolerability is the constraint |

Academic groups (MD Anderson, Dana-Farber, others) are mapping **synthetic-lethal pairs** to pin KRAS-addicted cells without clobbering normal tissue.

---

## Side effects: the practical limiter

Even with better scheduling, MEK/ERK drugs have familiar liabilities:
**rash/dermatitis, diarrhea, fatigue, retinal effects** (rare cardiotoxicity).  
DCIs try to **lower the toxicity “area under the curve”** while keeping the tumor under pressure. If the window holds, long-term use becomes realistic instead of a sprint to dose reduction.

---

## What this could mean for colon cancer

Direct KRAS drugs (sotorasib, adagrasib) help **G12C**, which is a minority in CRC. The common **G12D/G13D** set still leans heavily on MAPK, which makes **MEK/ERK** the logical flank.

If Immuneering’s readouts continue to trend in the right direction, **Phase 3 around 2026–2027** and **first pivotal readouts ~2028** are plausible.  
For CRC specifically, assuming expansion, **meaningful access in the early 2030s** is a reasonable (and optimistic) line of sight. Not a silver bullet—more like another gear to mesh with EGFR/chemotherapy backbones and, eventually, smarter KRAS-variant-specific agents.

---

### References and attributions

- Prior posts for context:  
  • [KRAS, EGFR, and Drugs](https://jamestsay-12.github.io/blog-site/science/2025/08/06/KRAS-EGFR-and-Drugs.html)  
  • [Targeted Colon Cancer Treatment Status](https://jamestsay-12.github.io/blog-site/science/2025/08/12/Targeted-Colon-Cancer-treatment-status.html)  
  • [Pan-RAS Inhibitors: Mechanism and Efficacy](https://jamestsay-12.github.io/blog-site/science/2025/08/13/Pan-Ras-Inhibtors-Mechanism-and-Efficacy.html)

- MAPK pathway figure and overview: [Wikipedia: MAPK/ERK Pathway](https://en.wikipedia.org/wiki/MAPK/ERK_pathway) (Image credit: *Fred the Oyster*).  
- Continuous vs Deep Cyclic schematic: *author’s illustration* — `/assets/img/science/deep cyclic.png`.  
- Immuneering materials and trial record: press releases linked above; [ClinicalTrials.gov NCT06208124](https://clinicaltrials.gov/study/NCT06208124?term=immuneering&rank=1).  
- Pancreatic data summary: *Targeted Oncology* link above.  
- CRC expansion probability: *Pharmaceutical Technology* link above.

---

*Personal note:* this is still a moving target. The idea isn’t to crown MEK inhibition—the idea is to **make it livable** and **keep the pathway cornered** long enough to matter, especially for KRAS variants where the direct shots still aren’t there.

*Standard disclaimer:* This is my read as a biotech scientist; it isn’t medical advice.
