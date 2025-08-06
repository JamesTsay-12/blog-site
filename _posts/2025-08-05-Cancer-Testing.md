---
layout: post
title: "What I learned when my biotech career collided with my mother's cancer diagnosis"
date: 2025-08-05
categories: Science
---

This post is in progress.  I'll dive into my family's current journey navigating the health system, cancer, and the utilization of the latest available technology from biotech.


# My Mom's Cancer Journey and the impact of Precision Medicine 

This is a personal reflection on the evolving landscape of genetic testing for cancer.  As both a biotech professional and the son of a cancer patient, I found myself caught between the promise of precision medicine and the harsh realities of clinical care. 

This is my story — a roller coaster ride of initial hope, frustration, despondency, and now renewed hope that we will be able to battle cancer more effectively with technology in the future.  

---

### The Early Days

My mom was diagnosed with Stage 3b colon cancer more than a decade ago. She had lymph node involvement, and underwent surgery to remove a large tumor from her colon. Chemotherapy followed — FOLFOX (with oxaliplatin) — which caused terrible side effects. After that, she frequently remarked “chemo is hell” and vowed never to go through it again.

Her oncologist at the time was elderly and didn’t seem to have any awareness of modern molecular diagnostics or targeted therapy. Within a couple of years, she was diagnosed with Stage 4 disease, with metastases in her lungs. She later had two separate surgeries to remove tumors from her lungs.

Miraculously, she remained cancer-free for a long time — possibly more than five years.

---

### The Pandemic and Recurrence

During the pandemic, my mom was hesitant to attend routine doctor visits. Eventually, troubling symptoms emerged: uncontrollable coughing and persistent back pain. A check-up with imaging — CT, X-ray, PET scan — revealed a recurrence with massive spread and multiple metastases in her chest.  This time, tumor removal through resection was not possible.

Meanwhile, I watched her suffer: collapsing in public, excessively coughing, dealing with severe back pain and physical discomfort.

---

### Chasing the Data

After working for a DNA sequencing company for more than decade, I knew about many of the rapid improvements for precision medicine both in diagnostics and new drug treatments, and I was optimistic that now our healthcare system could be better equipped to deal with cancer for my mom.

Weeks after her biopsy, I wanted to ensure her sample had been sequenced. I made several calls but couldn’t reach anyone who could confirm whether her tumor had undergone DNA sequencing. When I looked at her case file online, there was no mention of further diagnostics.

Eventually, I went with my parents to one of her oncologist appointments. The doctor started out doing some basic physical examinations, and looked over the scans he had with a very grim expression.  He asked my mom if she knew what the results meant, and then jumped straight into chemotherapy options. I interrupted — told him I worked in molecular diagnostics at a biotech company — and asked about targeted treatments.

He told me she had already had NGS done (next generation sequencing) and had KRAS mutations in her biopsied tumors, which made her ineligible for EGFR (epidermal growth factor receptor) drugs. Note: KRAS is a key protein involved in cell growth signaling pathways, and certain mutations in the KRAS gene can drive cancer. Whether a cancer is "druggable" often depends on the specific type of KRAS mutation present.

I pushed back. I mentioned new research for drugs, like adagrasib, which had recently been FDA approved for cancer patients with KRAS G12C mutations in combination with cetuximab (an EGFR drug) in the past year. He replied, matter-of-factly: “She has G12S.”

I could only say, “Oh…” because I didn’t yet know what that meant. I quickly searched my phone. It turns out, G12S is one of the worst KRAS mutations — not currently druggable, very rare, and with some of the lowest survival rates.

I’ll go deeper into the science of this in a supplemental section.

That moment revealed my emotional bias. I had hoped so badly that something could be done to save her, that I basically assumed there was a path.

---

### Reading the Report

I asked for her sequencing report. The oncologist said “sure,” left the room, and came back with a 7-page document. It detailed her diagnosis via NGS, listed her mutations, potential actionable outcomes, eligibility for drugs, and suggested clinical trials.

As I scanned the report, I felt a mix of curiosity and dread. It was impressively laid out and comprehensive. She had been sequenced with a TSO 500 (comprehensive tumor profiling panel) assay using Illumina’s NovaSeq (high throughput DNA sequencing) platform. It turns out, I had worked on the R&D team that developed the consumables for that platform — specifically the patterned flow cell (a nano-patterned technology that enables low cost, high throughput sequencing).

I felt proud that our technology had come this far. It was now covered by Medicare (at least through Kaiser Permanente in San Diego) and considered standard of care. But I was also discouraged by how little of that information translated into actual treatment options.

And why hadn’t anyone told us about the test? Why didn’t the oncologist just give us the report initially? Why wasn’t this sequencing mentioned in earlier visit summaries?

---

### The Timeline and Next Steps

The process to get the sequencing done took over three weeks:

- One week to collect a biopsy sample for sequencing
- One week for results
- One more week to schedule and attend an oncologist appointment

The disappointing report from sequencing revealed there was no recommended treatment possible.  With no other alternative, the doctor’s only option was to do chemo (an updated cocktail), along with Avastin, a drug that reduces vascular growth of tumors. At best, this would marginally extend my mom’s life.  However, my mom had already made it clear: she wanted a good quality of life, didn’t want chemo, and wasn’t going to entertain any updates for it.

I asked about the clinical trials listed in the report. The doctor was dismissive. “Your mom is the boss, you need to listen to her,” he said. “All those targeted therapies have major side effects and can be just as brutal as chemo.” That attitude surprised and really discouraged me since I had some (wrong) impression that targeted therapies would have much lower side effects.

In general, he seemed irritated by my line of questioning and said, “If there were a better way to treat her, I would have already recommended it to you.” He also remarked that those clinical trials were “all junk” — revealing he must have a great deal of frustration with our therapeutic pipeline as well.

I had a past skepticism that doctors were often out of date from the most recent research, and I believe it’s right to advocate for alternative treatments if you come from a place of real knowledge —mine was from reading peer-reviewed scientific articles and not from listening to some TikTok influencer. To be fair, this oncologist was clearly well-trained and impressively knowledgeable. I suspect we actually shared a deep, unspoken frustration — the helplessness of having no better options for someone we both wanted to help. That takes a toll on everyone involved.

Later in the appointment, my mom mentioned that another doctor had suggested radiation to relieve pain from her largest tumor.  This was pretty much the only thing the doctor expressed any optimism over: to increase the quality of my mom’s life for the remaining time she had left.  Thankfully, she did receive this treatment — and it reduced her pain significantly.

---

### The Bigger Picture

Current targeted therapies for metastatic colon cancer have only about a 6–8% response rate (see supplemental info). That’s a grim number. It frustrates me when I see people in the media constantly touting “cures” for cancer without context, providing false hope— even most of the legitimate breakthroughs apply to very narrow patient populations, and very few actually achieve remission.

Yes, we’re making progress. But effective, reliable cancer diagnosis and treatment is still a long way off. I’m currently extremely disappointed in the impatience and unwillingness of investors and our federal government to support these endeavors. I hope this environment will change in the near future so researchers, the biotech industry, and doctors can succeed in preventing the suffering caused by cancer.  I’ll expand more on that in a future article.

I do want to acknowledge that despite the currently low percentage of people who can benefit from precision medicine, the amount of people with stage 4 colon cancer is so large that many people (up to 30,000 people/year worldwide) can have a better life with treatment (depending on their healthcare system). So all of our efforts in fighting cancer are still extremely worthwhile!

As for my mom, it’s unlikely any new drug will be available in time to help.

---

### Final Thoughts and Recommendations

If you're reading this: please get your colonoscopy as early as your insurance allows — at 45, or earlier (40) if you have a family history. Colonoscopies can not only provide a definitive diagnosis but can also remove precancerous polyps before they turn malignant.

But this experience has also shown me where we're failing as an industry and healthcare system, and it's not for lack of trying.
The biotech professionals I work with put in long and stressful hours developing technologies they genuinely believe will save lives. The doctors I've met—including my mom's oncologist—are carrying the weight of delivering devastating news to families like mine, often with inadequate tools to offer real hope. These people are getting burned out and demoralized trying to bridge the gap between what we can test for and what we can actually treat. They deserve better support, and patients deserve the breakthroughs their dedication should be producing.

What I find extremely frustrating is the communication breakdown. When I had to interrupt my mom's appointment to ask about targeted therapies, that wasn't a failure of medical knowledge—it was a system that doesn't give doctors time to walk patients through their options and their reasoning adequately.  We have to directly ask for complex genomic reports with no bottom line/summary that a common person can understand. My mom shouldn't have needed a son in the industry to decode what her results meant.  I really wonder what most other people do!

I'm also disappointed by the impatience of investors and policymakers who expect quick returns on cancer research. The technology I helped build took many years to develop and deploy. The drugs that might have helped my mom are still in clinical trials because developing effective cancer treatments takes decades, not months. We can't keep pulling funding when the timeline doesn't match quarterly earnings reports.

My mom has been fighting this disease for over a decade with more courage than I could ever manage. The doctors treating her are doing everything they can with the tools available. The scientists and engineers developing new tools are working themselves to exhaustion. But we're letting all of them down by not committing to the long, expensive, often frustrating work of turning promising lab results into treatments that actually save lives.

Still, I remain hopeful because I've seen what dedicated people can accomplish when they have the resources and time to do it right. We just need to give them both.




For those interested, I’ll include a deeper dive into KRAS mutations and the current state of targeted therapies in a supplemental post.

---


#### Supplemental: KRAS Mutations and Targeted Therapy Stats

#### Global Colorectal Cancer Statistics
- Estimated new colorectal cancer cases worldwide (2022): ~1.9 million (Source: GLOBOCAN, WHO)
- Proportion of cases diagnosed at Stage 4: ~20–25%
- Approximate new Stage 4 cases/year: ~380,000

#### Percent Eligible for Targeted Therapy
- 6–8% response rate among Stage 4: ~22,800 to 30,400 people/year

#### Key Subtypes and Therapies
- **MSI-H Tumors (~5%)**: 30–60% respond to immunotherapy → ~2–3/100
- **BRAF V600E (~10%)**: 25–40% response to targeted combos → ~2–4/100
- **KRAS G12C (~4%)**: ~10–20% monotherapy, up to 60% in combos → ~1/100
- **HER2 Amplification (~2%)**: ~30% response rate → <1/100

#### Summary Impact
- ~20–25% of mCRC patients have actionable mutations
- Adjusted by response rates, ~6–8% benefit from current therapies

#### Caveats
- Response ≠ cure; ORR doesn’t include stable disease benefit
- Combinations and emerging drugs are improving outcomes
- Anti-VEGF and other non-targeted drugs not included in this count
- Tumor evolution may cause resistance

Precision medicine is helping thousands. The impact is small by percentage, but huge for the individuals and families who benefit.
