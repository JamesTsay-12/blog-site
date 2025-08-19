# Molecular Diagnostics in Colorectal Cancer – Standard of Care (Stage-Specific)

**Overview**


| Stage / Setting | Key Molecular Diagnostics | Technology | Output / Actionability | Frequency / Timing | Insurance Coverage (US) | Strength of Evidence / Guideline Tier |
|---|---|---|---|---|---|---|
| **Screening / Early Detection** | **Conventional:** Stool DNA (Cologuard), FIT, Colonoscopy [^A4]  | DNA methylation, stool DNA, protein | Early detection → diagnostic colonoscopy if positive | Every 1–3 years depending on modality | Widely covered (Medicare, most insurers) | USPSTF B / ACS Cat. 1 |
|  | **AI-assisted colonoscopy (CADe/CADx)**—adds real-time polyp detection/classification, **improves ADR** and reduces inter-observer variability; **cost-effective in high-volume settings** [^A1] | Deep learning/transformers integrated into colonoscopy stack | Higher adenoma detection; fewer misses → potential interval cancer reduction; workflow efficiency | At time of colonoscopy | Coverage varies by facility and payer; treated as equipment/service add-on | **Emerging** (supportive evidence from multi-study review) |
|  | **Blood-based screening (ctDNA methylation)** (e.g., FDA-cleared assays) — noninvasive option; reported **~85–90% accuracy** in asymptomatic populations (study cited in review) [^A2] | Plasma cfDNA methylation | Positive → diagnostic colonoscopy | q3 yrs (policy dependent) | Medicare for FDA-cleared assays; commercial evolving | ACS/USPSTF integration evolving; **Emerging** |
| **Stage I–II (Localized, Resectable)** | Universal MMR/MSI testing [^B2] | IHC, PCR, NGS | Lynch screening; predicts lack of benefit from adjuvant 5-FU in stage II dMMR | Once at diagnosis | Standard of care | NCCN Cat. 1 |
|  | Germline panel if Lynch suspected [^B1] | Germline NGS | Identifies inherited syndromes → cascade testing | Once if indicated | Covered if criteria met | NCCN Cat. 1 |
| **Stage II–III (Post-surgery / Adjuvant)** | **ctDNA MRD**—prognostic; ctDNA-positive post-op ⇒ high relapse risk; **more sensitive than CEA for recurrence prediction** [^A3] | Personalized or fixed-panel cfDNA NGS | Risk stratification; informs intensity of surveillance and adjuvant decisions | Baseline post-op, then q3–6 mo for 2–3 y | Medicare MolDX (assay-specific); commercial expanding | NCCN Cat. 2A (emerging) |
|  | Tumor profiling (RAS, BRAF, HER2, NTRK, KRAS G12C) [^B2] | Tissue or plasma NGS | Prognostic/predictive; guides options if relapse | Once at resection (or bank for relapse) | Covered | NCCN Cat. 1 (RAS/BRAF/MSI), 2A (others) |
| **Stage IV (Metastatic / Advanced)** | Somatic profiling (extended RAS/NRAS, BRAF, HER2, KRAS G12C, NTRK fusions, MSI/MMR) [^B2] | NGS panel (tissue ± plasma) | Targeted therapy selection; immunotherapy if MSI-H/dMMR | At diagnosis; repeat at progression | Medicare NCD 90.2; commercial | NCCN Cat. 1 (RAS/BRAF/MSI), 2A (others) |
|  | **ctDNA for response/resistance monitoring**—serial tracking correlates with progression and immunotherapy response; detects anti-EGFR resistance mutations [^A2] | Plasma NGS | Adjust therapy; consider EGFR holiday/re-challenge strategies | At progression and between lines | Coverage expanding | NCCN Cat. 2A (emerging) |
| **Surveillance (All stages post-treatment)** | **ctDNA MRD**—earlier molecular relapse detection vs imaging/CEA; supports intensified follow-up when positive [^A3] | cfDNA NGS | Early detection of recurrence; triage imaging | q3–6 mo for 2–3 y | Medicare MolDX; private payers variable | NCCN Cat. 2A (emerging) |
|  | CEA [^B5] | Immunoassay | Non-specific marker; adjunct to ctDNA/imaging | q3–6 mo ×2 y, then q6 mo ×3 y | Covered | NCCN Cat. 2B |

```mermaid
flowchart LR
    A[Screening<br/>(FIT, stool DNA, ctDNA blood tests)] --> B[Diagnosis<br/>(Colonoscopy, biopsy, histopathology)]
    B --> C[Molecular Profiling<br/>(NGS panel, MSI, RAS/BRAF, HER2)]
    C --> D[MRD Monitoring<br/>(ctDNA assays for recurrence risk)]
    D --> E[Surveillance<br/>(ctDNA, CEA, imaging)]

    classDef stage fill:#E6F2FF,stroke:#2B6CB0,stroke-width:2px,color:#1A365D;
    class A,B,C,D,E stage;

# References

[^1]: **JSMO Guideline (5th edition, 2023)** – Molecular Testing in Colorectal Cancer  
[PMC article digest](https://pmc.ncbi.nlm.nih.gov/articles/PMC10920993/?utm_source=chatgpt.com)

[^2]: **Joint Guideline (ASCP / CAP / AMP / ASCO)** – Molecular Biomarkers for CRC  
- [CAP summary & guideline page](https://www.cap.org/protocols-and-guidelines/cap-guidelines/current-cap-guidelines/molecular-biomarkers-for-the-evaluation-of-colorectal-carcinoma?utm_source=chatgpt.com)  
- [AMP teaching slides PDF](https://www.amp.org/AMP/assets/file/clinical-practice/CRCMMTeachingppt_FINAL.pdf?utm_source=chatgpt.com)

[^3]: **Review Paper: Molecular Biomarkers in CRC** – ctDNA & MRD testing  
[PMC open access review](https://pmc.ncbi.nlm.nih.gov/articles/PMC5971222/?utm_source=chatgpt.com)

[^4]: **Screening Guidelines**  
- [American Cancer Society CRC Screening Recommendations](https://www.cancer.org/cancer/types/colon-rectal-cancer/detection-diagnosis-staging/acs-recommendations.html?utm_source=chatgpt.com)  
- [NCI CRC Screening Fact Sheet](https://www.cancer.gov/types/colorectal/screening-fact-sheet?utm_source=chatgpt.com)

[^5]: **AGA Clinical Toolkit for CRC** – Screening & follow-up workflows  
[AGA CRC toolkit](https://gastro.org/clinical-guidance/guideline-toolkits/colorectal-cancer-toolkit/?utm_source=chatgpt.com)

[^A1]: Chitca DD, et al. *Advancing Colorectal Cancer Diagnostics from Barium Enema to AI‐Assisted Colonoscopy.* **Diagnostics (Basel)**. 2025;15(8):974. Highlights AI-assisted colonoscopy’s impact on adenoma detection, cost-effectiveness in high-volume settings, and its role alongside liquid biopsy.  
[PMC article](https://pmc.ncbi.nlm.nih.gov/articles/PMC12026282/)






| Stage / Setting                     | Key Molecular Diagnostics                             | Technology           | Output / Actionability                                                                                  | Frequency / Timing                          | Insurance Coverage (US) | Strength of Evidence / Guideline Tier |
|-------------------------------------|-------------------------------------------------------|----------------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------|--------------------------|-------------------------------------|
| **Screening / Early Detection**     | Stool DNA (Cologuard), FIT, Colonoscopy + optional blood-based ctDNA methylation (Guardant Shield, Epi proColon) [^4] | DNA methylation, stool DNA, protein | Early detection, identifies patients for colonoscopy                                                    | Every 1–3 years depending on modality       | Widely covered (Medicare, most insurers) | USPSTF B / ACS Category 1 |
| **Stage I–II (Localized, Resectable)** | MMR/MSI testing (universal for all CRCs) [^2]         | IHC, PCR, NGS        | Identifies Lynch syndrome, predicts benefit from adjuvant 5-FU                                          | Once at diagnosis                           | Standard of care, universally covered | NCCN Category 1 |
|                                     | Germline panel if Lynch suspected [^1]                | NGS panel            | Determines hereditary risk, family testing                                                             | Once if indicated                           | Covered if criteria met | NCCN Category 1 |
| **Stage II–III (Post-surgery, Adjuvant)** | ctDNA (MRD detection: Signatera, Guardant Reveal) [^3] | Personalized ctDNA   | Predicts recurrence risk, guides adjuvant chemo decisions                                               | Baseline post-surgery, then serial (q3–6mo) | Medicare covers in stage II–III (Signatera LCD) | NCCN Category 2A (emerging) |
|                                     | Tumor profiling (RAS, BRAF, HER2, NTRK, KRAS G12C) [^2] | NGS tumor panel      | Prognostic & predictive markers for recurrence risk, potential targeted therapy if relapse              | Once at resection                           | Covered | NCCN Category 1 (RAS/BRAF), 2A (others) |
| **Stage IV (Metastatic)**           | Extended RAS/NRAS, BRAF, HER2, KRAS G12C, NTRK fusions, MMR/MSI [^2] | NGS tumor panel, PCR | Guides targeted therapies (anti-EGFR if RAS wt & left-sided, BRAF inhibitors, HER2 targeted, immunotherapy if MSI-H) | Once at diagnosis of metastatic disease      | Covered | NCCN Category 1 (RAS, BRAF, MSI), 2A (others) |
|                                     | ctDNA profiling [^3]                                  | Plasma NGS           | Alternative if tissue inadequate; resistance mutation monitoring (e.g., EGFR resistance)                | Baseline and at progression                  | Increasingly covered | NCCN Category 2A (emerging) |
| **Surveillance (Post-treatment)**   | ctDNA MRD (Signatera/Guardant Reveal) [^3]            | Personalized ctDNA   | Detects molecular relapse earlier than imaging/CEA                                                      | Every 3–6 months in remission monitoring     | Medicare covered; private payers variable | NCCN Category 2A (emerging) |
|                                     | CEA blood test [^5]                                   | Immunoassay          | Traditional surveillance marker, limited sensitivity/specificity                                        | Every 3–6 months per guidelines              | Covered | NCCN Category 2B |

---

## References

[^1]: **JSMO Guideline (5th edition, 2023)** – Molecular Testing in Colorectal Cancer  
[PMC article digest](https://pmc.ncbi.nlm.nih.gov/articles/PMC10920993/?utm_source=chatgpt.com)

[^2]: **Joint Guideline (ASCP / CAP / AMP / ASCO)** – Molecular Biomarkers for CRC  
- [CAP summary & guideline page](https://www.cap.org/protocols-and-guidelines/cap-guidelines/current-cap-guidelines/molecular-biomarkers-for-the-evaluation-of-colorectal-carcinoma?utm_source=chatgpt.com)  
- [AMP teaching slides PDF](https://www.amp.org/AMP/assets/file/clinical-practice/CRCMMTeachingppt_FINAL.pdf?utm_source=chatgpt.com)

[^3]: **Review Paper: Molecular Biomarkers in CRC** – ctDNA & MRD testing  
[PMC open access review](https://pmc.ncbi.nlm.nih.gov/articles/PMC5971222/?utm_source=chatgpt.com)

[^4]: **Screening Guidelines**  
- [American Cancer Society CRC Screening Recommendations](https://www.cancer.org/cancer/types/colon-rectal-cancer/detection-diagnosis-staging/acs-recommendations.html?utm_source=chatgpt.com)  
- [NCI CRC Screening Fact Sheet](https://www.cancer.gov/types/colorectal/screening-fact-sheet?utm_source=chatgpt.com)

[^5]: **AGA Clinical Toolkit for CRC** – Screening & follow-up workflows  
[AGA CRC toolkit](https://gastro.org/clinical-guidance/guideline-toolkits/colorectal-cancer-toolkit/?utm_source=chatgpt.com)



| Stage / Setting | Assay / Biomarker | Technology | Output / Actionability | Frequency | Insurance Coverage | Clinical Notes |
|-----------------|-------------------|------------|------------------------|-----------|--------------------|----------------|
| **Screening (average risk, age ≥45)** | Stool DNA (mt-sDNA, e.g., Cologuard) | DNA methylation + mutation panel | Positive → colonoscopy | q3 yrs if negative | Medicare & most commercial | Higher sensitivity than FIT; lower specificity; better adherence. |
| **Screening (emerging)** | Blood-based CRC screening (Shield™) | cfDNA methylation | Positive → colonoscopy | q3 yrs (Medicare) | Medicare covers FDA-approved | May increase uptake in reluctant patients. |
| **All stages (at diagnosis)** | MMR IHC ± MSI PCR/NGS | IHC, PCR, NGS | Lynch screening; predicts ICI benefit | Once at diagnosis | Standard of care | Reflex MLH1 methylation if MLH1 loss. |

---

## Stage II (localized, resected)

| Assay / Biomarker | Technology | Output / Actionability | Frequency | Coverage | Notes |
|-------------------|------------|------------------------|-----------|----------|-------|
| Tumor MMR/MSI | IHC, PCR, NGS | MSI-H → no adjuvant 5-FU (stage II) | Once | Covered | MSI-H/dMMR stage II → avoid chemo. |
| MRD (ctDNA) | Personalized or fixed-panel cfDNA NGS | Detects residual disease → guides adjuvant chemo | Baseline post-op, then q3–6mo for 2 yrs | Medicare MolDX (Signatera, Guardant Reveal) | Strong prognostic value; driving clinical trials. |
| Germline testing (if indicated) | Germline NGS | Detects Lynch, FAP, MAP | Once | Covered with criteria | Triggered by young age/family history/MSI-high tumor. |

---

## Stage III (node-positive)

| Assay / Biomarker | Technology | Output / Actionability | Frequency | Coverage | Notes |
|-------------------|------------|------------------------|-----------|----------|-------|
| Tumor MMR/MSI | IHC, PCR, NGS | Lynch screen; ICI prediction if recurrent | Once | Covered | MSI-H less common in stage III; still important. |
| MRD (ctDNA) | cfDNA NGS | Detects clearance vs persistence after surgery → risk stratification | Baseline post-op, then q3–6mo | Medicare MolDX | May guide chemo escalation/de-escalation (ongoing trials). |
| Germline testing | Germline NGS | Lynch, FAP, MAP | Once if criteria met | Covered | Cascade testing key. |

---

## Stage IV (metastatic/advanced)

| Assay / Biomarker | Technology | Output / Actionability | Frequency | Coverage | Notes |
|-------------------|------------|------------------------|-----------|----------|-------|
| Somatic profiling (KRAS/NRAS, BRAF, HER2, NTRK, KRAS G12C, TMB) | NGS (tissue or plasma) | Guides targeted therapy & clinical trial selection | At diagnosis, may repeat on progression | Medicare NCD 90.2; commercial | RAS WT & left-sided → EGFR therapy; BRAF V600E → poor prognosis; HER2+ → trastuzumab; KRAS G12C → adagrasib/sotorasib. |
| Immunotherapy biomarkers | NGS, IHC | MSI-H/dMMR → pembrolizumab/nivolumab | At diagnosis | Covered | Actionable even after multiple lines. |
| Resistance monitoring | Plasma ctDNA NGS | Detects acquired KRAS/NRAS mutations on anti-EGFR | At progression | Expanding | May enable anti-EGFR rechallenge when resistant clone wanes. |
| Germline testing (if young or family history) | Germline NGS | Identifies inherited syndromes | Once if criteria met | Covered with criteria | Even in metastatic setting, informs family risk. |

---

## Surveillance (all stages post-treatment)

| Assay / Biomarker | Technology | Output / Actionability | Frequency | Coverage | Notes |
|-------------------|------------|------------------------|-----------|----------|-------|
| MRD (ctDNA) | cfDNA NGS | Detects recurrence earlier than imaging | q3–6mo for 2–3 yrs | Medicare MolDX | May replace/augment CEA in future SOC. |
| CEA | ELISA | Non-specific recurrence marker | q3–6mo x 2 yrs, then q6mo x 3 yrs | Covered | Low sensitivity/specificity but still standard. |

---

## Key Sources
- **NCCN Colon Cancer Guidelines** (2025)  
- **USPSTF CRC screening** recommendations (2021)  
- **Medicare NCD 90.2** – NGS in advanced cancer  
- **CMS MolDX LCDs** – MRD coverage (Signatera, Guardant Reveal)  
- **FDA approval of Guardant Shield™ blood CRC test**  
- **NCI PDQ** + NCCN for universal MMR/MSI testing

* **[Molecular Biomarkers for the Evaluation of Colorectal Cancer](https://pmc.ncbi.nlm.nih.gov/articles/PMC5971222/):** This article from PubMed Central provides a comprehensive overview of the biomarkers used in the management of colorectal cancer.

* **[The Consensus Molecular Subtypes of Colorectal Cancer](https://pmc.ncbi.nlm.nih.gov/articles/PMC4636487/):** This article from PMC provides a detailed explanation of the four consensus molecular subtypes.

* **[Molecular Testing in Colorectal Cancer: Diagnosis of Lynch Syndrome and Personalized Cancer Medicine](https://academic.oup.com/ajcp/article/137/6/847/1760533):** This article from Oxford Academic discusses the role of molecular testing in both hereditary and sporadic colorectal cancer.

* **[Current Update of Laboratory Molecular Diagnostics Advancement in Management of Colorectal Cancer (CRC)](https://www.mdpi.com/2075-4418/10/1/9):** This review from MDPI discusses the advancement of diagnostic technologies and their impact on CRC management.

* **[Insurance Coverage for Colorectal Cancer Screening](https://www.cancer.org/cancer/types/colon-rectal-cancer/detection-diagnosis-staging/screening-coverage-laws.html):** The American Cancer Society provides information on insurance coverage for colorectal cancer screening.

* **[Circulating Tumor DNA for Personalized Treatment of Colorectal Cancer (Annu. Rev. Med. 2024)](https://www.annualreviews.org/content/journals/10.1146/annurev-med-050322-030018):** Published in February 2024, this excellent review provides a comprehensive overview of the uses of circulating tumor DNA (ctDNA) in CRC management. It covers its application in detecting minimal residual disease (MRD) after surgery, monitoring for recurrence, and guiding therapy in the metastatic setting.

* **[NCCN Clinical Practice Guidelines in Oncology: Colon Cancer (Version 1.2025)](https://www.nccn.org/professionals/physician_gls/pdf/colon.pdf):** The NCCN guidelines are a critical resource for the standard of care in the US. The 2025 updates (and late 2024 versions) incorporate the latest evidence for molecular testing. They provide detailed recommendations on *RAS*, *BRAF*, MSI/MMR, and HER2 testing, and increasingly, guidance on the clinical utility of ctDNA for MRD assessment in stage II/III disease. *(Note: This link goes to the most current version, which is regularly updated).*

* **[ctDNA-Guided Adjuvant Therapy for Stage II Colon Cancer (NEJM Evidence, 2024)](https://evidence.nejm.org/doi/full/10.1056/EVIDoa2300264):** This article discusses the results and implications of recent major clinical trials that use ctDNA to guide adjuvant chemotherapy decisions in stage II colon cancer. It highlights how molecular diagnostics can help de-escalate treatment and spare patients from unnecessary toxicity.

* **[The Expanding Role of Molecular Testing in Colorectal Cancer (ASCO Educational Book, 2024)](https://ascopubs.org/doi/10.1200/EDBK_421557):** Published for the 2024 ASCO Annual Meeting, this article synthesizes the latest advances and future directions. It covers established biomarkers and explores emerging ones, including HER2 amplification, NTRK fusions, and the challenges of targeting KRAS mutations, providing a forward-looking perspective on personalized medicine in CRC.

* **[Liquid Biopsy in Colorectal Cancer: A Tool for the Future with Current Applications (JAMA Oncology, 2024)](https://jamanetwork.com/journals/jamaoncology/article-abstract/2814889):** This Viewpoint article from February 2024 summarizes the current clinical readiness of liquid biopsy in CRC. It clearly outlines where ctDNA testing is already standard of care (e.g., genotyping in metastatic disease) and where it is still investigational but promising (e.g., screening and MRD assessment).
