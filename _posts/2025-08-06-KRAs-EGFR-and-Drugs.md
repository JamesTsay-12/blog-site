---
layout: post
title: "Why KRAS Mutations Make EGFR Drugs Ineffective: A Precision Oncology Lesson"
date: 2025-08-06
categories: Science
---

In my previous post about my family's cancer journey, I touched on how molecular diagnostics are reshaping cancer treatment. One of the clearest examples of this is the interaction between **EGFR** and **KRAS** in colorectal and lung cancers. Understanding this pathway helps explain why certain therapies fail—and why personalized medicine is essential.

## The Role of EGFR in Normal Cells

**EGFR** (Epidermal Growth Factor Receptor) is a receptor tyrosine kinase that functions like an antenna on the cell surface. It receives external growth signals and transmits them into the cell to drive division and survival.

The signaling process works like this:

1. **Ligand Binding**: Growth factors like EGF bind to EGFR.
2. **Dimerization**: Two EGFR molecules pair up on the cell surface.
3. **Activation**: This activates their internal kinase domains.
4. **Downstream Signaling**: A phosphorylation cascade begins—EGFR activates **KRAS**, which activates **RAF**, then **MEK**, then **ERK**—ultimately triggering gene transcription and cell proliferation.

This pathway is tightly regulated in normal cells.

## How EGFR Drives Cancer—and How We Try to Block It

In some cancers, EGFR is **overexpressed** or **mutated**, leading to continuous growth signals. That’s where EGFR inhibitors come in.

There are two major classes:

- **Monoclonal antibodies** (e.g., *cetuximab*, *panitumumab*) block the **extracellular domain** of EGFR to prevent ligand binding and dimerization.
- **Tyrosine kinase inhibitors (TKIs)** (e.g., *gefitinib*, *erlotinib*) block the **intracellular kinase domain** of EGFR to stop phosphorylation and signaling.

These therapies can work well—**but only if the cancer relies on EGFR for growth.**

## Why EGFR Drugs Don’t Work in KRAS-Mutant Tumors

KRAS is a **downstream signaling molecule**. In its normal form, it acts like a switch that turns on when EGFR sends a signal. But in cancers with **KRAS mutations**, the switch is **stuck in the ON position**—it signals constantly, regardless of what's happening upstream.

This means:

- Blocking EGFR doesn’t stop the growth signal.
- KRAS keeps activating RAF → MEK → ERK.
- EGFR inhibitors become **clinically ineffective**.

This is why **KRAS mutation testing is mandatory** before giving EGFR-targeted drugs in colorectal and lung cancer.

### 📊 Summary Table

| Tumor Profile                | EGFR Active | KRAS Mutated | EGFR Inhibitor Effective? |
|-----------------------------|-------------|---------------|----------------------------|
| EGFR Overexpression         | Yes         | No            | ✅ Yes                     |
| EGFR Activating Mutation    | Yes         | No            | ✅ Yes                     |
| KRAS Mutation (e.g. G12D)   | Irrelevant  | Yes           | ❌ No                      |

## Visualizing the Pathway

*Insert signaling cascade diagram here*  
![EGFR-KRAS Pathway](your_image_path.png)

This diagram illustrates the signaling cascade from EGFR → KRAS → RAF → MEK → ERK → cell proliferation. It also shows where drugs like *cetuximab* intervene—and why they don’t work when KRAS is mutated.

## Not All KRAS Mutations Are the Same

The most common mutations in KRAS occur at **codon 12**, but others happen at codon 13 or 61. These point mutations subtly change the KRAS protein structure, altering its biochemistry and druggability.

| Mutation | Amino Acid Change | Prevalence in KRAS Mutations | Common Cancer Types        |
|----------|-------------------|-------------------------------|----------------------------|
| G12D     | Gly → Asp         | ~30%                          | Colorectal, Pancreatic     |
| G12V     | Gly → Val         | ~23%                          | Pancreatic, Lung           |
| G12C     | Gly → Cys         | ~13%                          | Lung (NSCLC), Colorectal   |
| G12A     | Gly → Ala         | ~6%                           | Colorectal                 |
| G12S     | Gly → Ser         | ~4%                           | Pancreatic                 |
| G13D     | Gly → Asp (codon 13) | ~7%                       | Colorectal                 |

*Source: Prior et al., Cancer Research, 2012; COSMIC Database*

## How the Shokat Lab Cracked KRAS G12C

For decades, KRAS was considered *“undruggable”*—its surface was smooth and lacked any obvious drug-binding pockets. But that changed with the work of **Kevan Shokat’s lab at UCSF**.

They discovered a unique vulnerability in the **G12C** mutation: the cysteine substitution allowed covalent binding of a drug molecule to an allosteric pocket when KRAS is in the **GDP-bound (inactive)** state.

This led to the development of:

- **AMG 510 (sotorasib)** – FDA-approved for KRAS G12C NSCLC  
- **MRTX849 (adagrasib)** – Also showing efficacy in lung and colorectal cancers

These drugs **selectively bind to KRAS G12C** and shut off its activity, marking the first real success in directly drugging KRAS.

> Cited: Ostrem et al., *Nature*, 2013 (Shokat Lab)

## Why G12C Drugs Don’t Work for G12D, G12V, and Others

Unfortunately, other common KRAS mutations like **G12D** or **G12V** do *not* introduce a cysteine at position 12. Without the reactive sulfur group, covalent binding is impossible.

New strategies are being explored:

- **Non-covalent inhibitors** (e.g., MRTX1133 for G12D)
- **KRAS degraders** targeting the whole protein for destruction
- **Upstream/downstream modulators** (SHP2, SOS1, ERK inhibitors)
- **Neoantigen vaccines and T-cell therapies** tailored to KRAS mutations

We’re now moving from a world of “undruggable KRAS” to “selectively druggable KRAS.”

## Final Thoughts

KRAS mutations are among the most frequent oncogenic drivers in cancer—and they’re a major reason some targeted therapies fail. But with better diagnostics and smarter drug design, we’re finally breaking through.

This is precision medicine in action. Knowing whether a tumor has a **KRAS G12D**, **G12C**, or no mutation at all is not an academic detail—it’s the difference between wasted time and effective care.

---

## References

1. Prior, I. A., et al. (2012). *A comprehensive survey of Ras mutations in cancer*. Cancer Research, 72(10), 2457–2467. https://doi.org/10.1158/0008-5472.CAN-11-2612  
2. Ostrem, J. M., et al. (2013). *K-Ras(G12C) inhibitors allosterically control GTP affinity and effector interactions*. Nature, 503(7477), 548–551.  
3. Canon, J., et al. (2019). *The clinical KRAS(G12C) inhibitor AMG 510 drives anti-tumour immunity*. Nature, 575, 217–223.  
4. Cox, A. D., et al. (2014). *Drugging the undruggable RAS: Mission possible?* Nature Reviews Drug Discovery, 13, 828–851.  
5. COSMIC: Catalogue of Somatic Mutations in Cancer. https://cancer.sanger.ac.uk/cosmic

---

Stay tuned for the next post, where I’ll explore the landscape of next-generation KRAS inhibitors and how biotech is tackling the challenge of G12D, G12V, and other difficult mutations.

