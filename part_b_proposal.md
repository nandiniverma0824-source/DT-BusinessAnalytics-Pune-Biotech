# Part B — Sourcing Strategy + Scale-Up Proposal
## DeepThought Business Analytics Internship

---

## Question 1: How Else Would You Find Federer Companies Across India?

---

### Method 1 — DSIR Recognised In-House R&D Unit List

**What it is:** The Department of Scientific and Industrial Research (DSIR) maintains a public directory of ~3,000 companies with formally recognised in-house R&D units. Available as a downloadable PDF from dsir.gov.in, updated annually.

**Why it works for this ICP specifically:** DSIR recognition directly evidences two Federer criteria simultaneously — C3 (Differentiation: the company has invested in structured R&D, not just production) and C4 (Technical DM: someone with scientific credibility had to establish and run the unit). It is a government-verified signal, not self-reported. Companies apply for DSIR recognition specifically to claim customs duty exemptions on research equipment — which means the R&D is real, not just a label.

**How to use it:** Filter the DSIR list by state (Maharashtra, Karnataka, Gujarat, Tamil Nadu, Telangana), then by industry category (chemicals, pharma, biotech, electronics, engineering). Cross-reference company names against Tofler/MCA for revenue band and promoter details.

**Expected yield:** ~800–1,000 companies after filtering. High quality — almost every company on this list passes C3 and C4 automatically.

**Limitation:** Skews toward established companies (10+ years old) that have formalised their R&D. Newer startups that haven't applied for DSIR yet will be missed.

---

### Method 2 — Industry Expo Exhibitor Directories

**What it is:** Trade expos publish exhibitor directories. Target expos for this ICP:
- **BioAsia** (Hyderabad) — biotech, pharma, life sciences
- **CPHI India** (Mumbai) — pharma, specialty chemicals, APIs
- **Aero India** (Bengaluru) — defence, aerospace, electronics
- **IMTEX** (Bengaluru) — precision engineering, machine tools
- **Agri Intex** (Coimbatore) — agri-inputs, seeds, biopesticides

**Why it works for this ICP specifically:** Exhibitors self-select for growth intent. A company spending Rs.2–10L on an exhibition booth is by definition actively pursuing new business — a direct C6 proxy. Expo segments map precisely to our industry baskets. Exhibitors at regulated-market expos (CPHI, BioAsia) are typically export-ready, which aligns with C3 and C5.

**How to use it:** Most expos publish exhibitor directories online; scrape or manually extract company name, website, and segment. For past expos, check archived exhibitor lists via the Wayback Machine.

**Expected yield:** ~600–800 companies across 6–8 expos after deduplication.

**Limitation:** Biased toward companies that can afford booths and have a marketing budget. Bootstrapped smaller MSMEs may be absent.

---

### Method 3 — USFDA / EU-GMP / WHO-PQ Approved Facility Lists

**What it is:** Public regulatory databases of approved manufacturing facilities:
- **USFDA:** fda.gov — searchable facility database, filterable by country and product category
- **EU-GMP:** EMA database of GMP-compliant manufacturers
- **WHO Prequalification:** extranet.who.int/prequal — product-by-product listing

**Why it works for this ICP specifically:** Regulatory approval directly evidences C1 (manufacturer — impossible to get USFDA approval without a physical facility), C3 (differentiation — commodity manufacturers do not pursue international regulatory approvals), and C5 (export tailwind — an FDA-approved plant is already serving regulated export markets). It is perhaps the strongest single-source filter for the Federer profile because the certification process verifies what cannot be faked on a website.

**How to use it:** Filter USFDA database to India. Remove known large-cap pharma (Cipla, Sun, Dr. Reddy's, Lupin). Remaining companies are mostly mid-size specialty manufacturers — exactly the target band.

**Expected yield:** ~300–400 companies after removing large-cap pharma.

**Limitation:** Heavy pharma/chemicals bias. Defence, precision engineering, and agri-inputs manufacturers are underrepresented.

---

### Method 4 — PLI Scheme Beneficiary Lists

**What it is:** Government of India publishes Production Linked Incentive (PLI) scheme beneficiary lists for: pharma, medical devices, specialty chemicals, electronics/IT hardware, food processing, textile machinery. These are public documents available from the respective ministry websites.

**Why it works for this ICP specifically:** PLI companies have formally committed to production growth targets to receive incentive payouts. This is a verified C6 growth signal — the company has put skin in the game with the government. PLI schemes specifically target domestic manufacturers, so the lists are free of multinationals and subsidiaries. Revenue band is implicit in PLI eligibility thresholds.

**How to use it:** Download PLI beneficiary lists from Ministry of Chemicals (pharma PLI), Ministry of Health (medical devices PLI), and Ministry of Electronics. Filter to target segments and cities.

**Expected yield:** ~400–500 companies across 4–5 PLI schemes.

**Limitation:** Minimum revenue thresholds in some PLI schemes exclude smaller companies (sub-Rs.50Cr). Skews toward the Rs.100–500Cr band.

---

### Method 5 — BSE SME / NSE Emerge Listed Companies

**What it is:** The BSE SME platform and NSE Emerge list smaller companies that have opted for public listing. Filter by industry sector (chemicals, pharma, biotech, defence electronics, medical devices, agri-inputs) and revenue band (Rs.50–500Cr).

**Why it works for this ICP specifically:** Listed companies have public financials — revenue band is known immediately from annual reports, eliminating one of the hardest data points to verify for unlisted companies. Director details are public (SEBI disclosure requirements), making promoter/technical DM verification fast. Ownership structure is transparent — PE controlling stakes, group subsidiaries, and foreign parent relationships are all disclosed in shareholding pattern filings.

**How to use it:** BSE/NSE provide sector-wise company master lists for download. Filter to manufacturing sectors and cross-reference against MCA for promoter details.

**Expected yield:** ~400–500 companies in target segments and revenue band.

**Limitation:** Covers only listed companies. The majority of Federer-profile Indian MSMEs are unlisted private companies — the BSE SME list is a supplement, not a primary source.

---

### Method 6 — LinkedIn Sales Navigator — Inverted Search

**What it is:** Instead of finding companies and then checking if the founder is technical, invert the search — find technical founders and then check if their company is a manufacturer.

**Search parameters:** Title = "Founder" OR "MD" OR "CMD" OR "Co-Founder" + Seniority = Owner + Industry = (target manufacturing sectors) + Location = (target cities) + Keywords = "PhD" OR "IIT" OR "IISc" OR "ex-ISRO" OR "ex-DRDO".

**Why it works for this ICP specifically:** Directly targets C4 — technical decision-maker. A PhD founder of a specialty chemicals company in Pune will appear in this search even if his company has no website and no DSIR recognition. This method surfaces hidden gems that no directory or regulatory list would capture.

**How to use it:** Sales Navigator export → CSV → cross-reference company names against MCA for revenue and registration details → verify product (C1) against company website.

**Expected yield:** ~400–600 profiles, mapping to ~300–400 unique companies.

**Limitation:** LinkedIn data is self-reported and often inaccurate for Indian MSMEs (company size, industry tags). Requires manual verification for each hit.

---

### Method 7 — Industry Association Member Directories

Key associations that concentrate Federer companies:
- **ABLE (Association of Biotech Led Enterprises):** India's primary biotech manufacturers association. Members are mostly SME biotech manufacturers — directly ICP-relevant.
- **Pharmexcil (Pharma Export Promotion Council):** Lists Indian pharmaceutical exporters; filterable by product category and export destination (regulated vs. semi-regulated markets).
- **ELCINA (Electronic Components & Semiconductors Association):** Defence and industrial electronics manufacturers.
- **Seed Association of India / FICCI Agri-Input:** Hybrid seed and specialty agri-input companies.

**Limitation:** Some directories are paywalled or infrequently updated. Heavy overlap with DSIR and expo lists — deduplication essential.

---

### Method 8 — Indian Patent Office (IPO) Filing Database

**What it is:** The Indian Patent Office publishes all patent applications and grants at ipindia.gov.in. Filter by: Applicant type = "company" + IPC classification codes relevant to target segments (A61K = pharma/biotech, C12N = microorganisms/enzymes, C07C = organic chemistry, H01L = semiconductor devices) + Filing date = last 3 years.

**Why it works for this ICP specifically:** Recent patent filings evidence C3 (differentiation — active IP generation, not just production) and C4 (technical DM — a scientist is running the company, not just a businessperson). A company filing 5+ patents in the last 3 years is definitionally growing its technical moat.

**Limitation:** Many Indian SMEs rely on trade secrets rather than patents. Some Federer companies have strong differentiation but no patent filings. Best used as a supplement to verify C3, not as a primary sourcing tool.

---

## Question 2: The 1,000-Company Proposal

### Goal and Key Constraint

Build a verified list of 1,000 ICP-qualified Federer companies across India within 30 calendar days.

The constraint is quality: 1,000 companies with evidence-backed scores on all 6 criteria — not a bulk dump of company names from a directory.

### Yield Assumptions

Based on the Part A research experience:
- Investigated ~80–100 companies → ~10–11 qualifying (first-pass yield ~12–14%)
- The assignment states ~30% yield after deeper research
- To reach 1,000 qualified companies: need to investigate ~3,500–4,000 companies

### The Funnel

```
Raw Universe (3,500–4,000 companies)
        ↓  Hard pre-filters: service company / MNC subsidiary / revenue ceiling / no website
Screened Pool (2,000–2,500)
        ↓  Automated 6-criterion AI scoring (Claude Haiku first pass)
First-Pass Qualified (1,200–1,400)
        ↓  Human QA on borderline cases + AI confidence flags
Final Verified List (1,000)
```

---

### Week 1 — Build the Raw Universe (Days 1–7)

**Goal:** Assemble 3,500–4,000 unique Indian specialty manufacturers with name, city, segment, and website.

**Day 1–2:** Download and parse structured sources — DSIR list, BSE SME/NSE Emerge company master files, USFDA India facility list. These are downloadable data files — fastest to process. Expected yield: ~1,200–1,500 companies.

**Day 3–4:** Scrape exhibitor directories from 6–8 target expos (BioAsia, CPHI India, Aero India, IMTEX, Agri Intex). Build Python + Playwright scrapers. Expected yield: ~600–800 companies.

**Day 4–5:** Extract association directories (ABLE, Pharmexcil, ELCINA). Query MCA data via Antigravity for target NIC codes (2423, 2424, 2113, 3841, 2660) + target states + paid-up capital Rs.1–100Cr. Expected yield: ~800–1,000 companies (noisy — requires filtering).

**Day 5–6:** LinkedIn Sales Navigator — technical founder search across target cities. Export to CSV. Expected yield: ~400–600 profiles → ~300–400 unique companies.

**Day 6–7:** Deduplication across all sources using fuzzy name matching (Levenshtein distance) + CIN number matching for listed companies. Website discovery for companies without URLs (Google search automation). **Target: 3,500–4,000 unique companies.**

---

### Week 2 — Automated ICP Scoring (Days 8–14)

**Goal:** Score all companies on 6 criteria using AI pipeline.

**Day 8–9:** Build and test scraper — for each company with a website, scrape homepage + /about + /leadership + /products + /news + /careers. Playwright handles JavaScript-rendered sites. 10-second timeout per page. Test on 50 calibration companies; verify scraper reliability.

**Day 10:** Build scoring pipeline. Prompt structure for Claude Haiku:
- Input: company name + website text (~8,000 tokens max) + MCA data (revenue band, director names)
- Output: JSON with C1–C6 scores (Strong/Moderate/Weak) + one-line evidence per criterion + confidence flag (high/low) + verdict
- Guardrails baked into prompt: flag if MCA director list contains "Limited" suffix suggesting parent company; flag if revenue appears >Rs.500Cr; flag if product description contains "services", "consulting", "testing"

Test on 15 calibration companies (5 known PASS, 5 known FAIL, 5 borderline). Require ≥12/15 correct before deploying at scale.

**Day 11–13:** Run scraper on full 3,500-company universe — 4 parallel workers, ~30 seconds per company = ~7–8 hours total compute time.

**Day 13–14:** Run Haiku scoring on all scraped companies — ~3 seconds per company = ~3 hours. Store results in master spreadsheet with confidence flags. **Expected first-pass results: ~1,200–1,400 companies at B-band (60+).**

**Estimated AI cost for this step:** Claude Haiku at ~Rs.0.40/company × 3,500 = Rs.1,400.

---

### Week 3 — Re-scoring and Human QA (Days 15–21)

**Goal:** Validate the AI-scored list; reduce false positives to produce a reliable 1,200-company shortlist.

**Day 15–16:** Run Claude Sonnet re-scoring on all borderline cases (score 40–65 from Haiku, or any criterion with low confidence flag). Estimated ~700 companies. Sonnet is better at nuanced judgment on C3 (differentiation) and C4 (technical DM) than Haiku.

**Estimated additional AI cost:** Sonnet at ~Rs.3.50/company × 700 = Rs.2,450.

**Day 17–19:** Automated QA flags — programmatically flag:
- C3 evidence mentions only "ISO 9001" or "CE mark" (baseline certifications, not differentiators)
- C6 evidence references news older than January 2023
- All 6 criteria scored Strong (suspiciously clean — verify manually)
- Company name contains "Trading" or "Exports" (string match missed by AI)

**Day 19–21:** Human QA on ~400 flagged companies — open website, verify 2–3 key claims, adjust scores. 3–4 minutes per company = ~25 hours total. Also spot-check 50 random strong-pass companies for quality control.

**Expected output end of Week 3:** ~1,200 verified companies.

---

### Week 4 — Final Assembly and Delivery (Days 22–30)

**Day 22–25:** Personalization hook generation for top 200 companies (priority outreach tier). Claude Sonnet prompt: "Given this specific company's most recent milestone, write one sentence for line 1 of an outreach email. Must be specific, factually verifiable, and recent (last 18 months)." Verify 100% of hooks against source before including.

**Day 25–27:** Final assembly — merge strong-pass + QA-verified pass. Verify count ≥1,000. Deduplicate any remaining overlaps.

**Day 27–29:** Format final deliverable — master CSV, summary dashboard (pass/fail breakdown by city, segment, revenue band), methodology document.

**Day 30:** Buffer for overruns.

---

### Summary by Week

| Week | Focus | Output |
|------|-------|--------|
| 1 | Sourcing | 3,500–4,000 unique companies with name, city, segment, website |
| 2 | Scraping + AI scoring | All companies scored; first-pass qualified: ~1,200–1,400 |
| 3 | Re-scoring + Human QA | Borderline re-scored; ~400 flagged reviewed manually; 1,200 verified |
| 4 | Assembly + hooks | 1,000 final companies in CSV; top 200 with personalisation hooks |

---

### Risk Mitigation

| Risk | Mitigation |
|------|-----------|
| Yield below 30% | Expand universe: add state industrial directories (MIDC, GIDC, TSIIC), add 2–3 more expo lists |
| Scraper blocked | Rotate user agents, add delays. Fall back to manual research for high-priority blocked sites |
| AI scoring accuracy <80% | Retune on calibration set. Split scoring: Haiku for C1/C2/C5 (factual), Sonnet for C3/C4/C6 (judgment) |
| QA bottleneck | Tighten automated flag rules to reduce manual review load |
| Deduplication errors | Fuzzy name matching + CIN cross-reference + manual review of top 50 suspected duplicates |

---

### Tools and Estimated Cost

| Tool | Purpose | Estimated Cost |
|------|---------|---------------|
| Claude Haiku API | First-pass scoring (3,500 companies) | ~Rs.1,400 |
| Claude Sonnet API | Borderline re-scoring (700 companies) + hooks (200) | ~Rs.3,500 |
| Antigravity | MCA data extraction | Licence provided |
| Playwright + Python | Website scraping | Free (open source) |
| LinkedIn Sales Navigator | Technical founder search, company enrichment | Licence provided |
| GitHub Copilot | Scraper and pipeline code assistance | Licence provided |
| Tofler Pro / Tracxn | MCA revenue verification, investor data | Licence provided |
| **Total AI + data cost** | | **~Rs.5,000** |

---

### Final Deliverables

1. **Master CSV** — 1,000 companies, each with: name, website, city, segment, products, revenue band, decision-maker (name + title + background), C1–C6 scores with evidence, Federer score, verdict, confidence flags
2. **Priority-200 list** — Top 200 companies with personalisation hooks ready for outbound
3. **Methodology document** — All sources used, scraper architecture, scoring prompt, QA process, yield rates at each stage
4. **Code repository** — All scraping scripts, scoring pipeline, data processing notebooks — fully reproducible
5. **Fail list** — All ~3,000 investigated-but-rejected companies documented with clear fail reasons
