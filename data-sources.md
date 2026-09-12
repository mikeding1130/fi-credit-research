# Data Sources

Per-issuer links live in [`universe.csv`](universe.csv). This file records *which document to pull* from each jurisdiction, and the regulator-level sources that are usually better than anything an issuer publishes about itself.

## What to pull, by jurisdiction

| Jurisdiction | The document that matters | What it gives you |
|---|---|---|
| **EU / EEA** | *Pillar 3 / Additional Pillar III Report* (quarterly or semi-annual, alongside results) | CET1 and the full own-funds bridge, RWA by risk type, the MDA-relevant buffer stack, IFRS 9 Stage 1/2/3 balances and coverage, LCR/NSFR, and the terms of every outstanding AT1 and T2 instrument (Annex — capital instruments main features) |
| **UK** | *Pillar 3 Report* (PRA rules, quarterly for large firms) | Same as above, plus the MREL stack — HoldCo senior sits where EU senior non-preferred does, and the difference is worth a note of its own |
| **Switzerland** | *Pillar 3 report* under the Swiss TBTF regime | Going- and gone-concern capital shown separately; AT1 write-down terms differ from the EU and are spelled out here |
| **US — G-SIBs / advanced approaches** | *Basel Pillar 3 Regulatory Capital Disclosures* (quarterly) plus the 10-Q | Standardised and advanced RWA, the SCB, CECL allowance roll-forward |
| **US — Category IV regionals** | **No Basel Pillar 3.** Use the 10-K / 10-Q and the quarterly earnings supplement, plus the FR Y-9C | ACL roll-forward and CECL modelling assumptions, capital ratios, NII sensitivity disclosure |
| **Canada — banks** | *Supplementary Regulatory Capital Disclosure* (quarterly, every Big Six bank publishes one) | CET1 under the OSFI CAR Guideline, RWA detail, LCR/NSFR, TLAC, and the terms of LRCN, preferred shares and NVCC subordinated debt |
| **Canada — insurers** | *LICAT* disclosure in the quarterly MD&A and financial supplement | Total ratio, base solvency buffer, available capital by tier. LICAT is a different regime from CET1 — the comparison is the point |
| **Singapore** | *Pillar 3 and Liquidity Disclosures* under MAS Notice 637 | Capital, leverage, liquidity, and the capital instrument annex |
| **Japan** | *Basel Pillar 3 Disclosures* (semi-annual, Japanese GAAP) plus the fixed income / creditor page | TLAC build, external TLAC ratio, subordinated instrument terms |

## Regulator-level sources

These are frequently better than issuer-published material, because they are standardised across issuers and therefore comparable.

| Source | Use it for |
|---|---|
| [SEDAR+](https://www.sedarplus.ca/home/) | Every Canadian continuous-disclosure filing in one place — prospectuses for LRCN and NVCC issues, where the actual instrument terms live |
| [SEC EDGAR full-text search](https://www.sec.gov/edgar/search/) | US 10-K / 10-Q / 8-K, and the S-3 / 424B prospectus supplements that carry preferred-share and sub-debt terms |
| [EBA EU-wide transparency exercise](https://www.eba.europa.eu/risk-and-data-analysis/risk-analysis/eu-wide-transparency-exercise) | Standardised, bank-by-bank EU data on capital, asset quality and exposures — the single best cross-issuer comparison set in Europe, and it is free |
| [Federal Reserve — FR Y-9C](https://www.federalreserve.gov/apps/mdrm/) / FFIEC UBPR | US bank holding company regulatory data, comparable across issuers where 10-Qs are not |
| [OSFI financial data](https://www.osfi-bsif.gc.ca/) | Canadian bank and insurer regulatory returns, and the CAR / LICAT guidelines themselves |

## Rules for citing

1. Cite the **document**, not the company: *Source: Nordea Pillar 3 Report, Q2 2026, p.42* — never *Source: Nordea website*.
2. Prefer the **regulatory disclosure over the earnings presentation.** Presentations are chosen by the issuer; Pillar 3 tables are prescribed by the regulator, which is exactly why they are comparable.
3. When a figure is derived rather than disclosed, say so and show the arithmetic.
4. When something is genuinely uncertain, mark it uncertain. That is a stronger signal than false precision.

---

*Links verified September 2026. Issuer sites reorganise; if a link 404s, the document title in the table above is what to search for.*
