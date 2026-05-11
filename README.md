# GCC Market Intelligence — a Claude Skill for B2B/B2G founders

> A free, open Claude Skill that helps founders from outside the Gulf scale their B2B/B2G startup into Saudi Arabia, the UAE, Qatar, Bahrain, Kuwait, and Oman — without burning 6 months and $200k learning the basics the hard way.

## Why this exists

If you are an operating or scaling B2B / B2G startup founder who has never sold into the GCC before, the cost of figuring out the region on your own is enormous. The information is scattered across consulting blogs, government PDFs, sovereign-fund press releases, Telegram groups, paywalled databases, and the heads of ~200 people who actually know how things work.

This skill compresses that into a structured briefing that Claude (or any compatible agent) can pull up in 30 seconds. It covers:

- **Country and city-level macroeconomic context** — Riyadh, Jeddah, Dammam, Madinah, NEOM, Abu Dhabi, Dubai, Sharjah, Doha, Manama, Kuwait City, Muscat, Duqm and more.
- **Detailed family maps** — ruling families (Al Saud, Al Nahyan, Al Maktoum, Al Qasimi, Al Nuaimi, Al Mualla, Al Sharqi, Al Thani, Al Sabah, Al Khalifa, Al Said) and merchant conglomerates (Olayan, Al Rajhi, Al Muhaidib, Al Futtaim, Majid Al Futtaim, Al Ghurair, Al Habtoor, Kanoo, Kharafi, Bahwan, and 30+ more) — with their commercial assets *and* government links.
- **National strategies** — Saudi Vision 2030, We the UAE 2031, D33, Operation 300bn, National AI Strategy, Qatar NDS3, Bahrain Vision 2030/2050, Kuwait Vision 2035, Oman Vision 2040.
- **Soft-landing programs** — NTDP, Garage, NEOM, MISA, MiSK, Hub71, in5, Sheraa, DIFC, ADGM, Tamkeen, KDIPA, Future Fund Oman, Madinah Tech Cultivator, and others — with eligibility, ticket size, what you actually get.
- **Events as channels** — LEAP, GITEX, FII, WGS, Web Summit Qatar, Bahrain Fintech Forward, Biban, Black Hat MEA, ADIPEC, Gulfood, Arab Health, IDEX — with cost / ROI realism.
- **Procurement mechanics** — Etimad (Saudi government), UAE federal vs. emirate, ICV scoring, RHQ rules.
- **Localization and compliance** — Saudization tiers, Emiratisation fines, Omanisation, PDPL, data residency, VAT, withholding tax.
- **Sovereign funds** — PIF, ADIA, Mubadala, ADQ, ICD, QIA, KIA, Mumtalakat, OIA, MGX, Alat, Lunate.
- **System integrators** — solutions by stc, Mobily Business, Elm, Ejada, e& enterprise, du Tech, Injazat, Core42, BCT.
- **Cultural cadence** — Ramadan, Hajj, summer, weekend, prayer, majlis, iftar relationship-building.

It also includes three working frameworks:

1. **Market sizing for the GCC** — adapted for the data sources, classification quirks, and expat/national split that break Western TAM models.
2. **Competitive intelligence template** — including how to find out who is already selling to a specific ministry or conglomerate.
3. **Customer development interview guide for GCC contexts** — what to ask, how to ask it, when English vs Arabic matters, what "send a proposal" actually means.

## Who this is for

Operating or scaling B2B / B2G startups from outside the GCC. Examples of the founder profile this is built for:

- Smart cities / IoT / sustainability companies pitching municipalities (Madinah Municipality, RTA Dubai, Sharjah Municipality).
- AI infrastructure / enterprise SaaS pitching G42, Core42, Aramco Digital, STC Solutions.
- Health-tech pitching MoH KSA, DoH Abu Dhabi, NUPCO procurement.
- Fintech engaging SAMA Sandbox, CMA Fintech Lab, ADGM RegLab, CBB Sandbox.
- Climate-tech / energy-tech pitching ACWA Power, Masdar, ADNOC, Aramco.
- Edu-tech / govtech pitching MoE, Tatweer, ADEK, KHDA.
- Mobility / drone / robotics pitching RTA, NEOM, Diriyah, Roshn.

If you are a Series A+ founder with a working product and 1–10 employees and need to enter the GCC in the next 6 months, this is for you. The Madinah Tech Cultivator Cohort 2 profile (deep-tech, $50k–$250k funded, pre-revenue to $100k MRR, B2B + B2G) was the anchor reference when building this skill.

## How to use the skill

### In Claude (claude.ai, Claude Code, Claude Desktop, API)

1. Clone this repo or download the folder.
2. Drop the `gcc-market-intelligence/` folder into your Claude Skills directory (`~/.claude/skills/` for Claude Code, or upload via the Skills UI in claude.ai).
3. Start a conversation that mentions any GCC country, city, family, program, event, regulation, or "Gulf market entry" — the skill triggers automatically.
4. Answer the three disambiguation questions when Claude asks: target country, buyer type, founder stage.
5. Get a focused briefing.

### In Codex, Cursor, Gemini CLI, Windsurf, Antigravity, and other agents that read `SKILL.md`

The skill follows the open Agent Skills specification (December 2025). Drop the folder into the agent's skill directory.

### Standalone

Even without an AI agent, the `references/` and `frameworks/` markdown files work as plain reading. Start with `SKILL.md`, then read the country file that applies to you.

## Structure

```
gcc-market-intelligence/
├── SKILL.md                              # entry point — what triggers the skill and how to use it
├── references/
│   ├── countries/                        # one file per GCC country (macro + cities)
│   ├── families/                         # ruling and merchant families
│   ├── procurement/                      # Etimad, UAE procurement, localization
│   ├── culture/                          # calendar, customer development
│   ├── sovereign-funds.md
│   ├── soft-landing-programs.md
│   ├── events-calendar.md
│   └── system-integrators.md
├── frameworks/
│   ├── market-sizing.md
│   ├── competitive-intel.md
│   └── customer-dev-interviews.md
└── assets/
    ├── intro-email-templates.md
    ├── pitch-deck-localization.md
    └── meeting-followup.md
```

## What this skill is NOT

- Not legal or tax advice. RHQ structuring, free zone vs. mainland licensing, PDPL compliance, and VAT registration all need qualified counsel.
- Not a substitute for a local adviser on the ground. The skill orients; the local person executes.
- Not a live database. Program ticket sizes, Saudization quotas, exemption rules, and RHQ thresholds change quickly. Every file has a "last verified" date; verify before committing capital.
- Not a guarantee of meetings, intros, or outcomes.

## Contributing

Pull requests welcome. Particularly valued:

- Corrections with sources.
- New named programs, events, system integrators, or family branches with verifiable detail.
- Sector-specific addenda (e.g. defense procurement, halal compliance, fintech sandbox specifics).
- Updates when a regulation moves — flag the file and the date.

Please do not contribute speculation about ruling-family internal dynamics, unconfirmed deal rumors, or anything that could be construed as private. The skill stays on public, verifiable, professionally-relevant facts.

## License

MIT. Use it, fork it, embed it, build on it.

## Acknowledgments

Built with reference to the [Madinah Tech Cultivator](https://madinahcultivator.com) Cohort 2 founder profile — deep-tech founders from 11 countries operating in smart cities, sustainability, mobility, energy, food security, and adjacent verticals. The skill is designed to help the next cohort, and every founder like them, save the months that would otherwise be spent learning what's in these files.
