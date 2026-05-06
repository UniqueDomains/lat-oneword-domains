# Available .LAT One-Word Domains (11,292)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C292%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .lat one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,292 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,292 domains · **Median ask:** $51.02 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `lat.csv` — public CSV extract (1,000 rows)
- `lat.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/lat-oneword-domains/main/lat.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| Acup.lat         | available | $40.98    | —             | 80             | 5      | 5      | namecheap       |
| finals.lat       | available | $1.99     | —             | 80             | 7      | 6      | name.com        |
| barup.lat        | available | $1.99     | —             | 82             | 2      | 6      | name.com        |
| geton.lat        | available | $1.99     | —             | 82             | 10     | 6      | name.com        |
| Apples.lat       | available | $40.98    | —             | 90             | 16     | 6      | namecheap       |
| edamame.lat      | available | $1.99     | —             | 80             | 9      | 7      | name.com        |
| headout.lat      | available | $1.99     | —             | 82             | 6      | 8      | name.com        |
| fitinto.lat      | available | $1.99     | —             | 84             | 2      | 8      | name.com        |
| chaitea.lat      | available | $1.99     | —             | 86             | 3      | 8      | name.com        |
| justin.lat       | available | $1.99     | —             | 58             | 38     | 7      | name.com        |
| joy.lat          | resell    | —         | —             | 78             | 42     | 3      | Spaceship, Inc. |
| nets.lat         | premium   | $2,500    | —             | 54             | 81     | 4      | name.com        |
| etc.lat          | available | $1.99     | —             | 58             | 34     | 3      | name.com        |
| Tools.lat        | resell    | —         | —             | 56             | 40     | 5      | Spaceship, Inc. |
| travelers.lat    | premium   | $2,500    | —             | 58             | 61     | 9      | name.com        |
| heroes.lat       | available | $1.99     | —             | 68             | 29     | 6      | name.com        |
| urban.lat        | resell    | —         | —             | 68             | 36     | 5      | Spaceship, Inc. |
| comics.lat       | premium   | $2,500    | —             | 68             | 24     | 6      | name.com        |
| commonground.lat | available | $1.99     | —             | 74             | 28     | 13     | name.com        |
| profile.lat      | resell    | —         | —             | 76             | 32     | 7      | Go Daddy, LLC   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,292 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/lat?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/lat?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=related_pricing)

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

This selection is entirely one-word .lat domains. The set includes short action words, dictionary terms, and brandable constructions such as Acup.lat, Finals.lat, Forces.lat, Geton.lat, Getup.lat, Popup.lat, Dogsit.lat, and Edamame.lat. For founders, the main question is whether a name is memorable, easy to say, and strong enough to carry a brand without extra explanation. For investors, the focus is tighter: whether the ask leaves room for a sensible spread and whether the word has clear resale appeal inside a niche extension. With a median ask of 51.02, low entry price may be a positive, but extension fit still matters more than volume.

- Prioritize words that sound natural before the .lat ending
- Check if the term is clear, memorable, and easy to spell
- Use the 51.02 median ask as a basic price reality check
- Avoid terms with obvious trademark or brand collision risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LAT One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LAT page](https://unique.domains/domains/tld/lat?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_lat_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
