# Methodology — Target Company Research
## DeepThought Business Analytics Internship
**City:** Pune | **Segment:** Specialty Biotech + Specialty Diagnostics & Life-Science Tools

---

## City Selection: Pune

Pune was selected as the target city for the following reasons:

**Density of regulated manufacturing:** Pune hosts over 150 USFDA-approved manufacturing plants — the highest concentration of any Indian city (KiTalent, March 2026). This means a disproportionate share of India's differentiated specialty manufacturers (C3 criterion) are Pune-based.

**Established biotech cluster:** Active industrial zones — Hinjawadi IT-BT Park MIDC, Bhosari MIDC, Chakan-Talegaon corridor, Viman Nagar — create a geographically verifiable cluster. When checking whether a company's "primary operational presence" is in Pune, these zones provide clear anchors.

**Academic spillover for technical founders:** NCCS (National Centre for Cell Sciences), IISER Pune, and NCL (National Chemical Laboratory) produce scientist-founders who commercialise their research in Pune. Gennova, Mynvax, and Immunoact all trace directly to this ecosystem.

**Active expansion pipeline:** Rs.2,800Cr+ committed to new biologics science parks in Pune's peripheral belts (Colliers India industrial outlook 2025). The cluster is attracting new investment, not stagnating.

**City definition applied:** A company counts as Pune-based if its founder, R&D team, or primary manufacturing facility is in Pune or the immediate surrounding industrial zones (Chakan, Talegaon, Hinjawadi, Bhosari, Viman Nagar). Registered office alone does not qualify. Companies with Pune manufacturing but Bengaluru or Delhi HQ were excluded unless primary operations are clearly in Pune.

---

## Segment Selection: Specialty Biotech + Specialty Diagnostics

Two segments were combined because Pune's cluster spans both:

- **Specialty Biotech (Basket A):** Recombinant proteins, fermentation services, biosimilars, cell therapy, mRNA platforms.
- **Specialty Diagnostics & Life-Science Tools (Basket A):** Diagnostic kits, antibodies, genomics tools, NGS platforms.

Both segments share: technical founders, USFDA/ICMR/WHO-PQ regulatory pathways, China+1 tailwinds, and PLI scheme eligibility. Combining them widened the qualifying universe while staying fully within Basket A.

---

## Research Process

### Step 1 — Universe Generation (~80–100 companies investigated)

| Source | Purpose |
|--------|---------|
| Google web search | Initial discovery of Pune biotech and diagnostic manufacturers |
| Built In Pune (builtinpune.in) | Curated biotech/pharma company lists |
| Tracxn | Revenue, MCA filings, employee count, funding, investor data |
| Tofler / ZaubaCorp / MCA RoC | Promoter/director details, paid-up capital, revenue bands |
| LinkedIn | Hiring signals, founder backgrounds, company activity |
| Company websites | Products, certifications, news sections, founder credentials |
| BSE/NSE filings | Revenue verification, annual reports, ownership structure |
| CRISIL Ratings | Revenue/growth data for HiMedia, Neogen |
| BioSpectrum India | Segment rankings — enzyme manufacturers, biotech top 50 |
| KiTalent (Mar 2026) | Pune pharma cluster dynamics |
| ICGEB website | Founder verification — Dr. Sanjay Singh (Gennova) |
| WHO PQ tracker | Prequalification status — Bioklone, Mylab |
| DCGI approval records | Immunoact CAR-T approval 2023 |
| BIRAC grant announcements | Mynvax and Immunoact funding verification |

### Step 2 — Immediate Disqualifier Screen

Three disqualifiers checked before full scoring:

1. **C1:** Is this a manufacturer of physical products — not a CRO, testing lab, or distributor? *Example disqualified: Vimta Labs (testing CRO).*
2. **City:** Is Pune the primary operational city? *Example disqualified: Bigtec Labs (Bengaluru HQ and manufacturing).*
3. **Ownership:** Is the company promoter-driven? *Example disqualified: Enzene Biosciences (Alkem subsidiary + PE investors).*

### Step 3 — Full Federer Scoring

Each surviving company scored on all 6 criteria with specific evidence (not assertions):

- **C3 (Differentiation):** Required specific patent, named regulatory approval, or verifiable first/only/pioneer claim. ISO 9001 alone rejected.
- **C4 (Technical DM):** Required direct academic credential evidence (named degree, institution, publications). Indirect signals scored as Moderate.
- **C6 (Growth Signals):** LinkedIn Jobs tab checked; website news section recency checked; revenue trend cross-checked Tracxn vs Tofler.

### Step 4 — Evidence Verification

Revenue: Tracxn MCA filing cross-referenced against Tofler and BSE/CRISIL.
Founder backgrounds: Company About page + LinkedIn + third-party (IIT faculty pages, ICGEB, publications).
Regulatory approvals: USFDA facility database, WHO PQ tracker, DCGI gazette.
Ownership: MCA director list + Tracxn investor tab — companies rarely disclose PE investors on their own websites.

---

## AI Hallucination Controls

| Risk | Guardrail Applied |
|------|------------------|
| AI inventing revenue | Always cross-checked against Tracxn/Tofler MCA filings |
| AI inventing founder credentials | Verified against LinkedIn + company website + third-party source |
| AI assigning wrong city | Confirmed registered address AND manufacturing address separately |
| AI classifying CROs as manufacturers | Verified: does the company produce a physical product? |
| AI missing subsidiary/PE flags | Always checked MCA directors list + Tracxn investor tab |
| AI over-scoring C3 on weak signals | Rejected ISO 9001 alone; required specific product IP or named approval |

**Specific AI disagreements:**
- **Enzene:** AI suggested Strong Pass. I overrode — Alkem subsidiary + PE capital fails promoter-driven criterion.
- **HiMedia:** AI flagged as potential pass. Two independent disqualifiers identified: revenue Rs.1,060Cr + city is Thane not Pune.
- **Praj Industries:** AI gave revenue Rs.300–500Cr. I flagged FY25 revenue may be approaching Rs.500Cr ceiling — noted as caveat, verify before contact.
- **Bioklone:** AI gave specific revenue figure without MCA filing source — marked as estimated, uncertainty noted.

---

## Key Segment Learnings

1. **Large-company trap:** Serum Institute, HiMedia, Piramal, Enzene — technically excellent but fail on revenue or ownership. Always verify current revenue first.
2. **City criterion is strict:** Bigtec, Bugworks, Premas — all strong Federer profiles but Bengaluru or Delhi-based. Fail city regardless.
3. **CRO confusion is common:** Many Pune biotech cluster companies are service firms that resemble manufacturers. Test: does it sell a physical product?
4. **IVD diagnostics is the Federer sweet spot in Pune:** Mylab, Genepath, Bioklone — Indian-promoter, technical-founder, clean profiles.
5. **Yield consistent with expectations:** ~80–100 investigated → 10–11 qualifying = ~12–14% first pass. Consistent with stated ~30% after deeper research at scale.
