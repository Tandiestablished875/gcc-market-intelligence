# Market Sizing for the GCC — A Working Framework

> Last verified: May 2026. Sources: GASTAT (KSA), FCSC (UAE), SCAD (Abu Dhabi), Dubai Statistics Center, PSA (Qatar), NCSI (Oman), CSB (Kuwait), iGA (Bahrain), GCC-STAT, IMF Article IV consultations, central bank reports.

## TL;DR — 60-second briefing

Standard Western TAM-SAM-SOM frameworks break in the GCC for four reasons:

1. **Expat/national split distorts headline numbers.** A "market of 35M Saudis" is actually ~22M nationals + ~13M expats with very different purchasing power and behavior. Same dynamic in UAE (90% expat), Qatar (88%), Kuwait (70%), Bahrain (55%), Oman (43%).
2. **Sectoral classification differs from Western standards.** GCC stats authorities follow ISIC Rev. 4 — but they aggregate differently. A "technology services" category might span what a US founder would call SaaS + consulting + telecom + government IT.
3. **Government share of GDP is enormous.** Public sector and SOE spending is often 40–60% of total demand. Pure-private TAM understates the market dramatically — but addressing the government share requires localization, RHQ, ICV, Etimad/Tamm registration.
4. **2024 GASTAT rebase added 14.1% to Saudi GDP overnight.** Statistical revisions are frequent and large. Always check what year your data uses and whether it pre- or post-dates a rebase.

This framework gives you a defensible bottom-up GCC TAM that survives investor scrutiny.

## Step 1 — Use the right data sources

Each country has a national statistical authority. Use that authority first, then triangulate.

| Country | Authority | URL | What it gives you |
|---|---|---|---|
| Saudi Arabia | GASTAT (General Authority for Statistics) | https://www.stats.gov.sa | Population, GDP, labor force, industry breakdowns, household income |
| UAE (federal) | FCSC (Federal Competitiveness & Statistics Centre) | https://fcsc.gov.ae | Federal aggregates, expat composition |
| Abu Dhabi | SCAD (Statistics Centre Abu Dhabi) | https://www.scad.gov.ae | Emirate-specific, oil and non-oil split |
| Dubai | Dubai Statistics Center (DSC) | https://www.dsc.gov.ae | Dubai-specific |
| Qatar | PSA (Planning & Statistics Authority) | https://www.psa.gov.qa | Population, GDP, labor |
| Bahrain | iGA Information & eGovernment Authority | https://www.iga.gov.bh | Demographic, sectoral |
| Kuwait | CSB (Central Statistical Bureau) | https://csb.gov.kw | Demographic, sectoral |
| Oman | NCSI (National Centre for Statistics & Information) | https://www.ncsi.gov.om | Strong Vision 2040 tracking |
| Regional | GCC-STAT | https://www.gccstat.org | Cross-GCC harmonized data — best for comparisons |

**Cross-reference with:**
- **IMF Article IV consultations** — published annually per country; macroeconomic context.
- **World Bank GCC reports** — sectoral deep-dives.
- **GCC central bank annual reports** — banking, payments, insurance breakdowns.
- **Sovereign-wealth-fund disclosures** — investment allocations indicate where capital flows.
- **Bain / McKinsey / BCG / PwC / Deloitte / Strategy& GCC reports** — useful for narrative, but they often cite each other circularly. Use for context, not foundation.

## Step 2 — Decompose population correctly

For B2C and consumer-economy market sizing, splitting nationals vs expats is essential. For B2B, both populations are workers/buyers but with different decision authority.

### Saudi Arabia (2025 estimates)
- Total: ~35.0M
- Saudi nationals: ~22.5M
- Non-Saudi (expats): ~12.5M (largely Asian — Indian, Pakistani, Bangladeshi, Filipino — with significant Arab populations)

### UAE (2025 estimates)
- Total: ~11.0M (FCSC + emirate-level estimates)
- Emirati nationals: ~1.2M (~11%)
- Expats: ~9.8M (~89%) — Indian, Pakistani, Filipino, Egyptian, Bangladeshi, Western

### Qatar (2025 estimates)
- Total: ~3.0M
- Qatari nationals: ~370k (~12%)
- Expats: ~2.6M (~88%)

### Bahrain (2025 estimates)
- Total: ~1.6M
- Bahraini nationals: ~720k (~45%)
- Expats: ~880k (~55%)

### Kuwait (2025 estimates)
- Total: ~4.9M
- Kuwaiti nationals: ~1.5M (~30%)
- Expats: ~3.4M (~70%)

### Oman (2025 estimates)
- Total: ~5.0M
- Omani nationals: ~2.85M (~57%)
- Expats: ~2.15M (~43%) — highest national share in GCC excluding KSA equivalent share

**Implications for TAM:**

For B2C:
- Premium consumer goods → bias toward expat western + national mid-upper segments.
- Mass-market consumer goods → expat south-asian + national bulk.
- Halal-specific → national + Arab expat focus.
- Family-oriented → national focus (larger household sizes among nationals).

For B2B:
- Government / public-sector buyers → effectively-100% national leadership; mixed-nationality operational layers.
- Family conglomerates → national ownership / leadership; expat operational layers.
- Free-zone tech companies → predominantly expat workforce, mixed nationality executive.

## Step 3 — Use bottom-up methodology, not top-down

The Western default ("MENA SaaS market is $X billion") is dangerous in the GCC. Top-down regional sizing typically aggregates incomparable economies (Egypt's $400B GDP behaves very differently from Qatar's $220B with 35x the per-capita income).

Better: bottom-up.

### B2G TAM bottom-up framework

```
B2G TAM (per country) = 
   Number of relevant ministries × average annual addressable spend per ministry
 + Number of SOEs/government-affiliated entities × average annual addressable spend  
 + Specific Vision-2030/2031/2040 program allocations relevant to your product
```

Sources:
- **KSA:** Annual budget published Dec by Ministry of Finance; breaks spend by ministry.
- **UAE federal:** Annual budget published by Ministry of Finance.
- **Abu Dhabi:** SCAD plus DoF (Department of Finance) disclosures.
- **Dubai:** Dubai Statistics Center plus Department of Finance.
- **Qatar:** PSA + Ministry of Finance budget.
- **Bahrain:** Ministry of Finance + EDB sectoral reports.
- **Kuwait:** Ministry of Finance + KAPP (Authority for Partnership Projects).
- **Oman:** Ministry of Finance + Tanfeedh portfolio.

Critical filter: **what fraction of that spend is addressable by foreign vendors?**
- Pure-defense work: very limited foreign access without partnerships.
- Healthcare IT: significant foreign access via SI partnerships.
- Smart-city / urban infrastructure: high foreign access via accelerator/pilot programs.
- Education / EdTech: moderate access, often through universities first.

Example: if your product is smart-water-management IoT and you're targeting KSA municipalities:
- Identify the 13 KSA regions × major municipalities (~50).
- Estimate average water-infrastructure annual capex per municipality.
- Estimate share addressable by your category (typically 0.5–3% of total water capex).
- Discount further by year-1 realistic capture (probably 1–5% of addressable).

### B2B-to-conglomerates TAM bottom-up framework

```
B2B TAM (per country) = 
   Number of relevant family conglomerates × average annual addressable IT spend per group
 + Number of relevant banks × average annual addressable spend  
 + Number of telecoms / SI partners × spend
 + Other large private buyers
```

- KSA: ~30 family conglomerates with revenues > $1B; ~12 banks; major SIs.
- UAE: ~50 family conglomerates with revenues > $1B; ~50 banks (including 50+ foreign branches); larger SI landscape.
- Qatar: ~10 major family conglomerates; ~17 banks.
- Bahrain: ~8 major family conglomerates; major financial-services concentration.
- Kuwait: ~15 major family conglomerates; ~10 banks.
- Oman: ~10 major family conglomerates; ~7 banks.

Use sovereign-wealth-fund portfolio disclosures (PIF, Mubadala, ADQ, ICD, QIA, Mumtalakat, OIA) to map their portfolio companies — these are addressable B2B buyers too.

### B2C TAM bottom-up framework

```
B2C TAM (per country) = 
   Target-demographic population × ARPU × adoption-rate-at-stage
```

Be specific about target demographics:
- Premium consumer products: focus on the ~3M households in UAE + ~2.5M households in KSA in the upper-income brackets.
- Halal-only: include national populations + Arab/Muslim expat segments.
- Western expat-focused: ~1M households in UAE + ~500k in KSA + smaller numbers in other GCC.

## Step 4 — Apply realistic year-1 capture rates

Founders pitching investors often confuse TAM with revenue projections. Use these benchmarks (rough — verify against your sector):

- **Year 1 in market (1 pilot customer):** 0.05–0.2% of SOM.
- **Year 2 (3–5 customers + 1 reference):** 0.3–1% of SOM.
- **Year 3 (scale phase):** 1–3% of SOM.

The fastest-growing GCC startups (Tabby, Tamara, Salla, Halan, Bayzat) have hit 1–3% SOM penetration in target segments within 18–24 months — but they had the benefit of either (a) consumer-facing demand pull or (b) sovereign-fund or strategic-partner backing. Pure outside B2B/B2G founders typically run slower.

## Step 5 — Apply localization friction discount

A US/EU founder's first 12 months in the GCC typically loses 6 months to friction: entity setup (1–3 months), procurement onboarding (2–4 months), Saudization/Emiratisation/Omanisation hiring (1–3 months), data-residency / cloud-region transition (1–6 months depending on sector), RHQ in KSA if applicable (3–6 months).

**Practical adjustment:** discount year-1 revenue assumptions by 30–50% relative to comparable European/US markets.

## Step 6 — Currency and conversion conventions

| Currency | Code | USD peg | Notes |
|---|---|---|---|
| Saudi Riyal | SAR | 3.75 SAR / USD | Pegged since 1986. Stable. |
| UAE Dirham | AED | 3.6725 AED / USD | Pegged since 1997. Stable. |
| Qatari Riyal | QAR | 3.64 QAR / USD | Pegged. Stable. |
| Bahraini Dinar | BHD | 0.376 BHD / USD | Pegged. High unit value (~$2.65/BHD). |
| Kuwaiti Dinar | KWD | ~0.308 KWD / USD | Pegged to a basket (not USD). Highest-valued currency in the world (~$3.25/KWD). |
| Omani Rial | OMR | 0.385 OMR / USD | Pegged. Second-highest unit value (~$2.60/OMR). |

**Conventions in pitches:**
- KSA / UAE: USD or local currency both work. SAR more common for KSA government; AED more common for UAE.
- Qatar / Bahrain / Kuwait / Oman: local currency increasingly expected, especially in government and family-office contexts.
- Always quote VAT-inclusive vs VAT-exclusive clearly. KSA 15% VAT vs UAE 5% vs Bahrain 10% vs Oman 5%.
- Withholding tax disclosures matter — see `references/procurement/localization-data-residency.md`.

## Step 7 — Build the TAM-SAM-SOM stack defensibly

```
TAM (Total Addressable Market) — 
  Total spend in your category across all 6 GCC countries × any year you choose.
  Bottom-up from country budgets + private-sector spend estimates.

SAM (Serviceable Addressable Market) — 
  TAM filtered for: countries you can actually serve (regulatory/licensing), 
  buyer types you can actually sell to (RHQ requirement etc.), 
  product fit (e.g. cybersecurity products may exclude government segments for national-security reasons).

SOM (Serviceable Obtainable Market) — 
  SAM × realistic capture in next 3–5 years, accounting for: 
  competitor density (SIs already entrenched), 
  localization friction (year-1 discount), 
  channel availability.
```

**Investor-defensible TAM looks like:**

> "Our SAM is the IT spend of the top 50 banks in KSA + UAE + Qatar (~$2.4B/year per Sovereign WP estimates), of which we can realistically address $180M (the ~7% category-fit subset). Our 5-year SOM target is 8% of that, or $14.4M ARR by year 5, building from $1.2M in year 1 (one anchor bank + RHQ structure)."

Specific. Bottom-up. References the named buyers. Sourced.

**Investor-shooting-down TAM looks like:**

> "MENA fintech is a $300B market and we plan to capture 1%."

Top-down. Unsourced. Unbounded geography. No defensible path.

## Common mistakes to avoid

- ❌ Using "MENA" as a proxy for GCC. MENA includes Egypt, Morocco, Tunisia, Algeria, Lebanon, Jordan — very different economies. Be specific.
- ❌ Citing "Middle East tech market" reports without naming the source and methodology.
- ❌ Multiplying total population × per-capita-GDP × your-cat-share. This double-counts expat purchasing power, which is variable.
- ❌ Ignoring the government share. In KSA, the government is ~40% of GDP demand. Excluding government means ignoring most of the market.
- ❌ Pricing in USD when government RFPs require SAR/AED/QAR. Bid in local currency.
- ❌ Forgetting that 2024 GASTAT rebase added ~14.1% to historic Saudi GDP figures. Pre-rebase reports understate KSA.

## What outside founders should know

- **Statistical authorities in the GCC have improved dramatically post-2020.** GASTAT, FCSC, SCAD, DSC are now publishing data quality comparable to OECD members. Use them directly, not just secondhand consultant reports.
- **Sovereign-wealth-fund websites are underused gold mines.** PIF, Mubadala, ADQ, QIA, OIA, Mumtalakat all publish portfolio company lists. These are your most promotable B2B prospects.
- **Vision document KPIs are your best long-term sizing inputs.** Saudi Vision 2030 published specific 2030 targets (e.g. "300% increase in non-oil GDP"); these are essentially government-commit-budget signals. Same with We the UAE 2031, Qatar NDS3, Bahrain Vision 2030, Kuwait Vision 2035, Oman Vision 2040.
- **The "single GCC market" myth.** While the GCC is a free-trade area, market entry is country-by-country in practice — different regulators, different procurement systems, different cultural buyer profiles. Plan country sequencing.

## Verify before committing capital

- **Population figures:** national statistical authorities publish updated estimates quarterly to annually. Verify your year before citing.
- **GDP figures:** check whether figures are pre- or post-rebase. KSA rebased in 2024 (+14.1%); other countries periodically.
- **Sector classification:** ISIC Rev. 4 differs from US NAICS. Verify category mapping.
- **Currency conversion:** all GCC currencies except KWD are pegged to USD. KWD pegged to a basket; ~0.5% intraday volatility possible.

## Related references

- `frameworks/competitive-intel.md` — finding out who's already selling where.
- `frameworks/customer-dev-interviews.md` — validating TAM assumptions with buyers.
- `references/sovereign-funds.md` — capital flow signals.
- `references/countries/` — country-by-country data and context.
