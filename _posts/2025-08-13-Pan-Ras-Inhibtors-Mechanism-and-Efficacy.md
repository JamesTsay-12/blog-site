---
layout: post
title: "Pan-RAS Inhibitors: Mechanism, Mutation Coverage, and Current Evidence"
date: 2025-08-13
categories: Science
---
This blog is in progress

# Pan-RAS Inhibitors: Mechanism, Coverage of KRAS Mutation Classes, and Current Evidence

**Disclaimer**
This article is a product of my own research into the literature and collaboration with AI.  I'm still checking for accuracy, and this is not medical advice.


### Overview  

Pan-RAS inhibitors—such as **RMC-6236 (daraxonrasib)**—represent a promising new frontier in targeting KRAS-driven cancers. Unlike mutation-specific drugs that only target G12C, these agents aim to inhibit active RAS across multiple isoforms and mutant alleles by exploiting a conformational mechanism. This post explores **how they work**, why they should **theoretically cover most RAS mutations**, and what **evidence** currently exists to support their effectiveness.

---

##  1. Mechanism of Action: The Pan-RAS “Tri-Complex” Strategy

- **Target: Active (GTP-bound) RAS**, not the GDP-bound "off" state.
- **Key players**:
  - A **small molecule ligand** with affinity for cyclophilin A (CypA)
  - **Cyclophilin A (CypA)**: a host protein that forms a **binary complex** with the ligand
  - **RAS-GTP**: when active, its **switch II/effector lobe surface** is exposed

- **Mechanism**:
  1. Ligand binds CypA → forms a **binary ligand·CypA** scaffold.
  2. That composite binds RAS-GTP → creates **ternary tri-complex** (ligand·CypA·RAS(ON)).
  3. This **sterically blocks effector binding** (e.g., RAF, PI3K), shutting down downstream signaling.  
    ([pubs.acs.org](https://pubs.acs.org/doi/10.1021/acs.jmedchem.4c02314), [pmc.ncbi.nlm.nih.gov](https://pmc.ncbi.nlm.nih.gov/articles/PMC11149917/))

- **Selectivity for GTP-bound RAS** arises because:
  - GDP-bound RAS does not present the appropriate binding surface.
  - The tri-complex approach relies on **cooperative affinity**, not high affinity of the ligand alone.

---

##  2. Mutation Coverage: Which KRAS Variants Are Targetable?

### Theoretically Covered (Pan-RAS)
- Common codon 12–13 mutations: **G12D, G12V, G12S, G13D**, etc.
- **Less common, non-codon-12 mutations**: K117N, A146T (exon 4)
- **Wild-type RAS** in tumors with RAS hyperactivation via upstream signals

### Mechanistic Rationale
- All active-state RAS alleles share structural features at the switch II/effector lobe, enabling tri-complex binding.
- High-and continuous GTP-loading (e.g., fast nucleotide exchange for K117N) logically increases the pool of RAS in the ON state—thus increasing susceptibility to tri-complex binding.

### Caveats
- **Codon-12/13 mutants** (especially G12D/V) have been most rigorously studied; **K117N/A146** exhibit distinct biophysical behavior and signaling output, potentially affecting drug sensitivity.  
  ([pmc.ncbi.nlm.nih.gov](https://pmc.ncbi.nlm.nih.gov/articles/PMC2943514/))
- Experimental datasets show **highest pharmacological potency** in KRAS G12X models; data for rarer alleles remain sparse.

---

##  3. Evidence to Date

### Preclinical Studies
- **Biochemical assays**: Validate tri-complex formation and blockade of RAS–RAF binding across KRAS/NRAS alleles.  
- **Cell line models**:
  - Strong suppression of MAPK signaling in KRAS G12X and NRAS Q61 mutants.
  - Activity includes some wild-type RAS contexts when upstream drivers are hyperactive.  
  ([pmc.ncbi.nlm.nih.gov](https://pmc.ncbi.nlm.nih.gov/articles/PMC11149917/))

- **In vivo xenografts**:
  - Tumor regressions in G12D/V lines.
  - Emerging data show efficacy in G12S, Q61R, and some WT-RAS-driven models.

### Early Clinical Findings
- **Phase I (NCT05379985)**:
  - Reported acceptable safety and pharmacokinetics in patients with various RAS mutations.
  - Disease stabilization and tumor shrinkage reported in KRAS-mutant CRC and pancreatic cohorts.  
  ([clinicaltrials.gov](https://clinicaltrials.gov/study/NCT05379985), [ir.revmed.com](https://ir.revmed.com/news-releases/news-release-details/revolution-medicines-presents-updated-data-rmc-6236-monotherapy))

- **Abstract data (AACR, ASCO GI)**:
  - Dose-dependent inhibition of downstream RAS signaling in tumor biopsies.
  - Responses observed across multiple KRAS mutations, though most frequent in codon-12 cases.

---

##  4. Practical Perspective: Mutation-by-Mutation Breakdown

| KRAS Mutation | Likely Sensitivity to Pan-RAS Inhibitor | Notes |
|---------------|------------------------------------------|-------|
| G12D/G12V     | High                                     | Strong preclinical/vivo data; most potent coverage. |
| G12S/G13D     | Moderate to High                         | Biochemical coverage inferred; less well characterized. |
| K117N/A146    | Possible                                 | Active-state is elevated; data limited and context may vary. |
| Q61 Mutations | Moderate                                 | Some suppression shown in NRAS Q61 models. |
| Wild-type RAS | Variable                                 | Dependent on upstream activation; may require biomarker selection. |

---

##  5. Conclusions & Considerations

- **Mechanistically broad**: Pan-RAS inhibitors are well-designed to target the active state across multiple mutations—offering a unified approach where mutation-specific drugs cannot.
- **Most evidence today supports G12D/V coverage**, with emerging proof-of-concept for rarer alleles.
- **Unknowns remain** for less common mutations (K117N, A146T); cell-line and animal models are needed.
- **CRC-specific biology** (high EGFR/SHP2 feedback, wild-type RAS redundancy) may limit monotherapy, calling for **combination strategies** (e.g. +EGFR, +MEK, +SHP2) to optimize efficacy.
- **Clinical experience is emerging**, with early stabilization and tumor responses across mutation types—tumor type and co-mutations matter.

---

### Final Thought  
Pan-RAS inhibitors like RMC-6236 are a significant advance in KRAS-targeted therapy. They promise to address a broader mutation landscape than any previous generation of drugs. While **G12D/V coverage looks strong**, the real test will be through ongoing trials—especially for rarer variants like K117N. If you're researching or communicating these topics, highlighting both the **mechanistic rationale** and appreciating the **nuances per allele** will resonate strongly with technical and translational audiences.

---


##  Supplemental

Expanding on rarer KRAS mutations like **K117N**:

Mechanistically,**RMC-6236 (daraxonrasib)** should have activity against *KRAS K117N*, but the strength of that activity in CRC is uncertain and likely lower/less predictable than for common *G12X* alleles.

---

### Why it should work (mechanism)

**RMC-6236** is a **pan-RAS, “RAS(ON)” tri-complex inhibitor**: it binds **active, GTP-loaded RAS** and, via cyclophilin A recruitment, blocks effector engagement (e.g., RAF) across multiple RAS isoforms/alleles—not just *G12C*. That design is **mutation-agnostic** in principle. [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10245607/) | [ClinicalTrials.gov](https://clinicaltrials.gov/study/NCT04956637)

***K117N* (exon 4)** alters the nucleotide pocket: Lys117 normally stabilizes guanine and promotes hydrolysis; **K117N enhances nucleotide exchange**, shifting KRAS toward the **GTP-bound (ON) state**, which is exactly the state **RMC-6236** targets. [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4297316/)

---

### Nuances/caveats specific to K117N in CRC

* **Exon 4 mutants (*K117N/A146*)** can show **distinct biochemistry and signaling output** compared with codon-12/13 mutants. Some models reported **lower steady-state RAS-GTP** despite increased exchange, alongside KRAS dependence and recurrent copy-number gain—so “how ON” the protein is can vary by context. This could **modulate drug sensitivity** to ON-state inhibitors. [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4297316/) | [AACR Journals](https://aacrjournals.org/clincancerres/article/21/8/1935/79963/KRAS-Allele-Specific-Oncogenicity-and-Drug)

* Early clinical/preclinical summaries of **RMC-6236** show **broad activity across RAS-mutant tumors**, with **strongest potency in *KRAS G12X*** lines; activity **“beyond *KRAS G12X*”** (including *NRAS Q61*) has been demonstrated, but **allele-specific data for *K117N* aren’t yet clearly reported**. Thus, activity is plausible but **not yet clinically proven** for *K117N* mCRC. [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10245607/) | [Revolution Medicines](https://ir.revmed.com/static-files/87803e3a-965a-4632-9c2b-e48f7d98305c)

* **CRC biology** (strong EGFR/SHP2-mediated feedback and WT-RAS signaling) can blunt RAS-pathway inhibitors; combinations (e.g., with EGFR/SHP2/MEK blockade) may be needed to maximize effect, regardless of the KRAS allele. [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9344833/)

---

### Bottom line

From first principles and available data, ***K117N* creates an ON-state KRAS that RMC-6236 is designed to hit**, so **mechanistic sensitivity is expected**. However, **direct *K117N*-specific clinical evidence in CRC is limited**, and CRC-specific feedback loops may necessitate **combinations**. If you’re tracking this for patients or trial design, I’d classify *K117N* as **biologically compatible** with **RMC-6236**’s mechanism but **evidence-limited** pending allele-resolved readouts from ongoing trials. [ClinicalTrials.gov](https://clinicaltrials.gov/study/NCT04956637)
