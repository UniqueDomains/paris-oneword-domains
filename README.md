# Available .PARIS One-Word Domains (4,729)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-4%2C729%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-4%2C729%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .paris one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 4,729 rows · **Live catalog:** 4,729 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/paris`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/paris?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./paris.csv">CSV</a> / <a href="./paris.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PARIS search](https://unique.domains/domains/tld/paris?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PARIS search](https://unique.domains/domains/tld/paris?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PARIS one-word domain catalog.

### Files

- `paris.csv` — public CSV extract (4,729 rows)
- `paris.json` — public JSON extract (4,729 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/paris-oneword-domains/main/paris.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| invalid.paris      | available | $51.98    | —             | 70             | 91     | 7      | namecheap       |
| found.paris        | resell    | $51.98    | —             | 70             | 45     | 5      | GoDaddy.com LLC |
| android.paris      | premium   | $363.60   | —             | 78             | 95     | 7      | name.com        |
| test.paris         | available | $51.98    | —             | 72             | 89     | 4      | namecheap       |
| move.paris         | resell    | $51.98    | —             | 78             | 42     | 4      | GoDaddy.com LLC |
| affinity.paris     | premium   | $363.53   | —             | 78             | 81     | 8      | name.com        |
| indeed.paris       | available | $51.98    | —             | 86             | 85     | 6      | namecheap       |
| launch.paris       | resell    | $51.98    | —             | 91             | 39     | 6      | GoDaddy.com LLC |
| entrepreneur.paris | premium   | $359.90   | —             | 82             | 80     | 12     | name.com        |
| ally.paris         | available | $51.98    | —             | 68             | 85     | 4      | namecheap       |
| pool.paris         | resell    | $51.98    | —             | 66             | 39     | 4      | GoDaddy.com LLC |
| march.paris        | premium   | $362.65   | —             | 70             | 80     | 5      | name.com        |
| orange.paris       | available | $65.99    | —             | 88             | 83     | 6      | name.com        |
| pin.paris          | resell    | $51.98    | —             | 74             | 33     | 3      | GoDaddy.com LLC |
| name.paris         | premium   | $364.66   | —             | 82             | 76     | 4      | name.com        |
| grandprix.paris    | available | $51.98    | —             | 76             | 83     | 10     | namecheap       |
| deliver.paris      | resell    | $51.98    | —             | 76             | 32     | 7      | GoDaddy.com LLC |
| habitat.paris      | premium   | $413.40   | $413.40       | 74             | 66     | 7      | namecheap       |
| axle.paris         | available | $51.98    | —             | 74             | 83     | 4      | namecheap       |
| delivery.paris     | resell    | $51.98    | —             | 76             | 31     | 8      | GoDaddy.com LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 4,729-row public sample | 4,729 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/paris?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/paris?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PARIS One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PARIS page](https://unique.domains/domains/tld/paris?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_paris_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
