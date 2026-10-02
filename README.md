# Available .LAT One-Word Domains (29,375)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-29%2C375%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .lat one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **29,375 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 29,375 domains · **Median ask:** $80.10 · **High-demand under $2,500:** 67

**Last updated:** 2026-10-02
**Canonical page:** `https://unique.domains/domains/tld/lat`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/lat?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./lat.csv">CSV</a> / <a href="./lat.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LAT search](https://unique.domains/domains/tld/lat?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LAT search](https://unique.domains/domains/tld/lat?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LAT one-word domain catalog.

### Files

- `lat.csv`, public CSV extract (1,000 rows)
- `lat.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/lat-oneword-domains/main/lat.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                      |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------ |
| bph.lat     | available | $1.99     | $32.49        | high           | low    | 3      | namesilo                       |
| aide.lat    | resell    | —         | —             | high           | low    | 4      | NameCheap, Inc.                |
| soy.lat     | premium   | $715      | $715          | high           | low    | 3      | dynadot                        |
| csr.lat     | available | $1.99     | $26.97        | high           | low    | 3      | dynadot                        |
| debt.lat    | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC               |
| ally.lat    | premium   | $2,600    | $2,600        | high           | high   | 4      | namecheap                      |
| fis.lat     | available | $1.99     | $32.49        | high           | low    | 3      | namesilo                       |
| space.lat   | resell    | —         | —             | high           | medium | 5      | Dynadot Inc                    |
| flor.lat    | premium   | $812.50   | —             | high           | low    | 4      | name.com                       |
| gur.lat     | available | $1.80     | $40.98        | medium         | low    | 3      | namecheap                      |
| change.lat  | resell    | —         | —             | high           | medium | 6      | Spaceship, Inc.                |
| gran.lat    | premium   | $710.10   | $710.10       | high           | low    | 4      | porkbun                        |
| jpl.lat     | available | $1.99     | $32.49        | medium         | low    | 3      | namesilo                       |
| drones.lat  | resell    | —         | —             | medium         | low    | 6      | —                              |
| lucy.lat    | premium   | $2,600    | $2,600        | high           | low    | 4      | namecheap                      |
| keg.lat     | available | $1.24     | $26.08        | high           | low    | 3      | spaceship                      |
| fashion.lat | resell    | —         | —             | high           | medium | 7      | Soluciones Corporativas IP, SL |
| rosa.lat    | premium   | $845      | $845          | high           | low    | 4      | namecheap                      |
| leg.lat     | available | $1.99     | $32.49        | high           | low    | 3      | namesilo                       |
| gourmet.lat | resell    | —         | —             | high           | low    | 7      | GoDaddy.com, LLC               |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 29,375 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 67 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/lat?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/lat?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list contains 11,324 one-word .LAT domain names covering everyday terms, compound words, and short brandable strings. The .LAT extension pairs a compact footprint with broad naming flexibility, making it suitable across industries. With a median asking price near $93, many names in this set are within reach for early-stage founders, while investors can scan the full range for TLD coverage and pricing patterns. Updated daily, this selection reflects current availability and ask prices across the .LAT namespace.

- 11,324 available one-word .LAT domains in this selection
- Median asking price near $93 across listed names
- Mix of short, brandable, and compound-word .LAT names
- Updated daily to reflect current .LAT pricing and availability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LAT One-Word Domains*. Version 2026-10-02. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LAT page](https://unique.domains/domains/tld/lat?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
