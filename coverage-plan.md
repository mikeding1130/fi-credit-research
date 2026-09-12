# Coverage Plan — Weeks 3 to 13

One note per week. Each week is a **question**, not a company: a note that covers one issuer in isolation cannot say anything about relative value, and relative value is the whole point.

Every week has a **primary** — the name the note is built on — and **comparators**, which exist to make the primary's number mean something. Issuer assignments are in [`universe.csv`](universe.csv); source links and the document to pull are in [`data-sources.md`](data-sources.md).

| Week | Dates | The question | Primary | Comparators |
|---|---|---|---|---|
| **W3** | Sep 21–27 | Does the spread between AT1 and Tier 2 compensate for the actual difference in loss-absorption risk, or only for the difference in ratings? | ING | Nordea |
| **W4** | Sep 28–Oct 4 | Across one issuer's whole stack — senior preferred, SNP, T2, AT1 — does the spread ladder reflect the real order in which losses land? | BNP Paribas | Barclays, UBS |
| **W5** | Oct 5–11 | Two banks at the same tier with the same rating and different asset quality: is the spread difference big enough? | Santander, Handelsbanken | Société Générale, UniCredit, Danske |
| **W6** | Oct 12–18 | US regional provisioning: where in the cycle is the allowance, and what does CECL hide that IFRS 9 staging would have shown? | Fifth Third | Regions, Huntington, Truist |
| **W7** | Oct 19–25 | How far is a US G-SIB from its binding capital constraint once the stress capital buffer and two quarters of organic RWA growth are taken into account? | JPMorgan | Bank of America, Citigroup, Wells Fargo |
| **W8** | Oct 26–Nov 1 | Canadian banking at the sector level: where is the provisioning cycle, and is the LRCN market pricing it? | RBC, TD | Scotiabank, BMO, CIBC, National Bank |
| **W9** | Nov 2–8 | LICAT against CET1: two capital regimes, two sets of constraints — where does the market misprice the difference? | Manulife, Sun Life | RBC (the CET1 side of the comparison) |
| **W10** | Nov 9–15 | Asia ①: how a large Asian bank actually builds to TLAC, and what the instrument mix tells you about the sponsor's assumptions | Mizuho | Standard Chartered |
| **W11** | Nov 16–22 | Asia ②: USD funding structure and offshore liquidity — who is funding long-dated dollar assets with short-dated dollar liabilities, and what does it cost | Standard Chartered | DBS, OCBC |
| **W12** | Nov 23–29 | Asia ③: how local-government and property debt transmits into a banking system's asset quality, and where it becomes visible in disclosure | *system level — no single issuer* | Mizuho, DBS, OCBC |
| **W13** | Nov 30–Dec 6 | The call from the previous ten weeks I now think was wrong — and why | *chosen from W3–W12* | — |

## Why the sequence runs Europe → US → Canada → Asia

Europe first because the AT1 and Tier 2 markets are deepest there: real prices, many comparable issuers, and the most complete public capital disclosure. That means the earliest notes — the ones written while the method is still being worked out — have the most external data to check them against.

Canada sits in the middle rather than first, despite being the home market, because a sector-level note is harder to write well than a single-issuer note and benefits from the practice.

Asia comes last because it carries the highest compliance sensitivity, and because it is the differentiated series — better written once the format is settled.

## The Asia series is written at system level

W10 to W12 cover the Chinese and Hong Kong banking systems as **systems**: the TLAC framework and how issuers meet it, the structure of offshore dollar funding, and the transmission from local-government debt to asset quality. They do not carry buy or sell views on named Chinese issuers.

This is a deliberate design choice, and it is the better research regardless of the compliance reason: the interesting question in that series is mechanical, not idiosyncratic. Mizuho, Standard Chartered, DBS and OCBC provide the disclosed, non-affiliated comparators that make the system-level argument concrete.

## Coverage priority

The priority column in `universe.csv` is the order in which names are actually needed, not a quality ranking:

- **1** — used in W3–W5. Data pulled and models built first.
- **2** — used in W6–W9.
- **3** — used in W10–W12.

If a week runs short of time, the primary is written and the comparators are cut to one. A note with one comparator is thin; a note with none is not research.
