# Competitive Intelligence in the GCC — A Working Framework

> Last verified: May 2026. Sources: Etimad portal (KSA), Tamm (Abu Dhabi), Dubai Now, TendersAlerts, MAGNiTT, Wamda, government press releases, sovereign-fund portfolio disclosures, public RFP archives.

## TL;DR — 60-second briefing

GCC competitive intelligence is harder than Western markets because:
- Private companies don't have to file financials (most family conglomerates disclose nothing).
- Press releases over-state wins; competitors rarely publish losses.
- The "real" deal flow is often hidden in tender-award announcements, sovereign-fund disclosures, and regional event speaker lists rather than press wires.

But the GCC has unique transparency too: **government tender portals publish award history**. With patience, you can map exactly who is selling what to which ministry — information that's effectively impossible to obtain in most Western markets.

This framework gives you a reproducible method for: identifying competitors, mapping their customer base, understanding their pricing, and predicting their next moves.

## Step 1 — Identify your competitors (the right set)

### Three layers of competition in the GCC

1. **Global incumbents who already have GCC presence.** Microsoft, AWS, Oracle, SAP, Salesforce, Cisco, Palo Alto, ServiceNow, IBM, Accenture, Deloitte Digital — all have regional offices, regional resellers, and named GCC customers. Find them in: customer logos on regional websites + press releases + sovereign-fund / SOE annual reports.

2. **Regional incumbents.** Companies that grew up in the GCC and dominate locally: Solutions by stc, Elm, Ejada, SBM, Naseej (KSA); Injazat (now part of e&), Core42, Presight, du Tech, Khazna Data Centers (UAE); BCT, Mannai, MEEZA (Qatar); BFC (Bahrain). For most enterprise B2B categories these are the actual competition, not Salesforce.

3. **Direct startup competitors.** Other foreign or local startups in your category. Find them via MAGNiTT, Wamda, Crunchbase, AngelList, regional startup directories.

### How to find them

- **Tender portals (where applicable):**
  - **Etimad** (KSA): https://etimad.sa — searchable government RFPs and award announcements. Foreign vendors need an account; partner with a local agent if no RHQ.
  - **Tamm** (Abu Dhabi): https://www.tamm.abudhabi — Abu Dhabi government services + tender announcements.
  - **Dubai Now**: https://www.dubai.gov.ae — Dubai government tenders (some).
  - **MOM Bahrain Tender Board**: https://www.tenderboard.gov.bh — Bahrain government tenders.
  - **MOMRA / regional municipalities** (KSA): each region has procurement portals.
  - **Public Authority for Industry / KAPP** (Kuwait): https://www.kapp.gov.kw.
  - **Etimad Oman / Mazoon**: https://etimad.om — Oman government tenders.

- **TendersAlerts / DG Market / globalvendor-net** — third-party aggregators.

- **Sovereign-fund portfolio disclosures** — PIF, Mubadala, ADQ, QIA, KIA, OIA, Mumtalakat publish portfolio companies. If a fund invested in your competitor, you'll see it.

- **MAGNiTT** — best regional startup database; tracks funding rounds, sector, geography. Useful for direct competitor mapping.

- **Wamda** — regional startup news. Sometimes covers losses, not just wins.

- **Regional event speaker lists** — LEAP, GITEX, FII, WGS, Web Summit Qatar. Speaker bios reveal who's actually winning and who's just hyping. Cross-reference 2024 and 2025 speakers in your category — repeat speakers are real players.

- **Linkedin search** — "[your category] manager" + "Saudi Arabia" / "UAE" / "Qatar" reveals where local skills exist. Their employer = active competitor or buyer.

- **Vendor lists in sovereign-fund / SOE annual reports** — Aramco, ADNOC, EGA, Mubadala publish "Top 10 vendors by spend" or similar. Highly revealing.

## Step 2 — Map their customer base

For each competitor, build a customer map:

### Public information sources

- **Customer-logo walls on company websites** — but assume ~30% of these are pilots that never became revenue contracts. Treat as leads-to-investigate, not as proof.
- **Case studies / press releases** — usually overstate impact and revenue. Useful for relationship mapping not financial scoring.
- **Etimad / tender portal award history** — searchable by vendor name. Reveals which government entities have actually awarded contracts and at what value.
- **Annual reports of public entities** — for listed companies (Aramco, ADNOC L&S, ADQ-listed companies, Tadawul-listed conglomerates, DFM-listed), 10-K-equivalent disclosures sometimes name top suppliers.
- **LinkedIn job postings** — "X (vendor name) experience required" in job posts reveals what software the hiring company uses.
- **Conference case-study presentations** — competitors often present customer wins at LEAP, GITEX. Recording, slides, and post-event reporting are searchable.

### Inferential techniques

- If a competitor has a regional office in Riyadh and 12 of their LinkedIn employees list "Aramco" as a previous employer, they likely have an active Aramco deployment.
- If a competitor sponsored a specific ministry's annual event, they likely have a contract or contract-in-progress with that ministry.
- If a competitor's press release names a Sheikh / Minister / family principal, they have a real relationship — but the photo-op event doesn't necessarily mean a signed contract.

### A concrete example

Competitor: "AcmeAI" (hypothetical).
Sources used:
- AcmeAI website lists 6 GCC logos: NEOM, PIF, SABIC, Mubadala, ADNOC, Aramco.
- LinkedIn search: 8 AcmeAI employees in Riyadh, 4 in Abu Dhabi, 2 in Dubai. Their bios mention previous employers including STC, Aramco, Etihad, and ADNOC.
- Etimad: AcmeAI has won 3 tenders, total disclosed value SAR 12M (~$3.2M) — 2 with the Ministry of Health, 1 with MoHRSD.
- Press: AcmeAI announced a Series B with participation from PIF's startup arm (Sanabil 500 graduate) in early 2025.
- GITEX 2025: AcmeAI presented case study with Mubadala portfolio company "Hub71 GovTech Stack".
- Conclusion: AcmeAI has ~$3.2M+ disclosed government revenue in KSA, growth backed by sovereign-fund capital, and probably 6–10 active enterprise contracts. Strong competitor. Their weakness: no presence outside KSA / Abu Dhabi yet — Qatar / Kuwait / Oman are open.

## Step 3 — Map their pricing

GCC pricing intelligence is hard because contracts aren't generally public. Sources:

- **Tender award disclosures** — Etimad publishes some award values. Use historical awards to triangulate per-customer ARR.
- **Annual budget documents** — KSA / UAE budgets sometimes itemize software-license categories.
- **Customer-side off-record conversations** — the most reliable source. In customer-development interviews ask: "What price ranges have you seen for [your category]?" Buyers will often share.
- **System integrator partners** — SIs typically have visibility into multiple vendors' price points. They won't share specifics but will share ranges.
- **MAGNiTT / Bessemer / regional VC reports** — sometimes publish revenue multiples that imply per-customer ARR.

**Pricing gotchas in the GCC:**

- Many enterprise contracts are denominated in local currency and include FX risk-sharing clauses.
- Multi-year deals often have built-in escalation clauses tied to UAE/Saudi CPI.
- Payment terms are often longer than in Western markets — 60–90 days is normal; 120 days for government.
- VAT inclusive vs exclusive matters — KSA 15%, UAE 5%, Bahrain 10%, Oman 5%, Qatar/Kuwait 0%.
- "Bundled" deals (license + implementation + support) hide unit pricing. Unbundle in proposals to reveal real pricing.

## Step 4 — Predict their next moves

Competitive intelligence isn't just historical mapping — it's prediction. Watch:

### Hiring signals
- A competitor opening 5+ KSA-based roles signals capacity buildout. Within 6 months they'll have new sales coverage.
- A competitor hiring a former Aramco / ADNOC / Mubadala executive signals a strategic account push for that entity.
- A competitor hiring an Arabic-fluent ex-government person signals B2G expansion.

### Financial signals
- Sovereign-fund investment = strategic regional commitment. Mubadala / PIF / ADQ / QIA backing implies multi-year regional play.
- Local partnership announcements (with stc, du, Aramco, ADNOC, Mubadala) signal channel buildout.
- Free-zone license registrations are public — DIFC, ADGM, DMCC, in5, NEOM Tech Cultivator, Riyadh Garage publish new tenants. Cross-reference monthly.

### Event signals
- Sponsoring or speaking at LEAP / GITEX / FII / WGS signals "we want to be visible in this market." Watch tier-1 sponsors particularly.
- Hosting their own customer events in Riyadh / Dubai / Doha signals customer-base sufficient to attract them.

### Regulatory signals
- A competitor pursuing a SAMA / CMA / CBUAE / FSRA / DFSA / QFCRA / CBB / CBK / CBO sandbox = upcoming sandbox-exit launch in 12–24 months.

## Step 5 — Use competitive intelligence to position

The point of competitive intel isn't to publish a competitive matrix. It's to inform your positioning. Three GCC-specific positioning angles:

### 1. Localization positioning
If your competitors are global incumbents (Microsoft, Salesforce, Oracle), your differentiator is local hosting, Arabic language, ICV, Saudization-friendly. Frame your pitch around what they CAN'T do.

### 2. Vision-alignment positioning
If your competitors are regional generic SIs (Solutions by stc, BCT), your differentiator is deeper technical excellence + alignment with a specific Vision pillar. Frame your pitch around the specific Vision 2030 / We the UAE 2031 / NDS3 / Vision 2040 KPI you address.

### 3. Speed positioning
If your competitors are deeply-embedded incumbents with multi-year SI partnerships, your differentiator is time-to-pilot (6 weeks vs 9 months). Frame your pitch around pilot velocity and POC structure.

## Specific tools and queries

### Etimad search workflow
1. Register a Saudi account (foreign vendors need a local agent or RHQ-affiliated entity).
2. Search by category code (using GASTAT industry codes).
3. Filter by award date, ministry, value range.
4. Export results to CSV.
5. Aggregate by vendor and by buyer to build your competitive map.

### LinkedIn Sales Navigator workflow
1. Search current employees of competitor + filter to KSA / UAE / Qatar / Bahrain / Kuwait / Oman.
2. Sort by tenure (longest = institutional knowledge; shortest = recent hire signals new project).
3. Look at "previous companies" patterns — reveals what skills they're acquiring and from whom.
4. Save searches; review monthly.

### Google + advanced operators
```
site:linkedin.com "AcmeAI" "Saudi Arabia"
site:etimad.sa "AcmeAI"
"AcmeAI" "Riyadh" filetype:pdf
"AcmeAI" "case study" 2024 OR 2025
```

### Regional VC / startup data
- **MAGNiTT** ($)— subscribe for sector / geography filtered deals data.
- **Wamda** — free; less structured but valuable for news.
- **Crunchbase + Pitchbook** — global coverage, weaker on private GCC deals.
- **Forbes Middle East** — annual rankings of family conglomerates, banks, fintechs.

## What outside founders should know

- **GCC competitive intelligence rewards patience.** A 4-week investigation can reveal more than 4 months of secondary-market research because most signals are scattered, not aggregated.
- **Talk to regional VCs.** Bessemer Middle East, BECO, MEVP, Saudi-based VCs (Aramco's Wa'ed, STV, Riyad Capital), UAE-based VCs (Mubadala, Shorooq, COTU, Wamda Capital), Qatar-based (QIA-affiliated), Bahrain-based (Mumtalakat), Oman-based (Phaze) — they know the deal flow. They'll often share intel for the cost of a coffee.
- **Build a "competitive deck" you don't share externally.** Keep it for internal positioning + investor conversations. Update quarterly.
- **Document your competitive losses obsessively.** Lost deals in the GCC are repeatable — same competitor wins for the same reasons. Track win/loss by competitor to spot patterns.

## What NOT to do

- ❌ Don't bash competitors in customer meetings. GCC business community is small; reputational damage propagates fast.
- ❌ Don't make claims about competitor weaknesses you can't substantiate. If a buyer asks "Why are you better than X?" — answer with your strengths, not their weaknesses.
- ❌ Don't assume Western analyst-firm GCC reports (Gartner, IDC, Forrester) reflect the actual deal flow. They underweight regional players significantly.
- ❌ Don't publish your competitive analysis on your website / blog. GCC buyers and competitors read everything; you reveal your hand.

## Verify before committing capital

- **Competitor customer claims:** ask 2+ people inside the named customer to confirm. Customer-logo walls overstate.
- **Competitor revenue estimates:** sovereign-fund disclosures and tender awards are more reliable than CEO claims at conferences.
- **Competitor pricing:** triangulate from 2+ buyer-side sources before adjusting your own pricing.
- **Regulatory standing:** if competitor claims sandbox / accreditation, verify directly with regulator (SAMA, CBUAE, etc.).

## Related references

- `frameworks/market-sizing.md` — how to size what your competitors are addressing.
- `references/system-integrators.md` — major SIs and their existing vendor relationships.
- `references/sovereign-funds.md` — sovereign-fund portfolios as competitive map.
- `references/procurement/saudi-etimad.md` — how Etimad actually works.
- `references/procurement/uae-procurement.md` — Tamm and other UAE procurement portals.
