# Available .FANS One-Word Domains (12,493)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C493%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fans one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,493 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,493 domains · **Median ask:** $120.43 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/fans`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/fans?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./fans.csv">CSV</a> / <a href="./fans.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FANS search](https://unique.domains/domains/tld/fans?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FANS search](https://unique.domains/domains/tld/fans?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FANS one-word domain catalog.

### Files

- `fans.csv` — public CSV extract (1,000 rows)
- `fans.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fans-oneword-domains/main/fans.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| Acup.fans         | available | $13.98    | —             | 80             | 5      | 5      | namecheap       |
| barup.fans        | available | $13.98    | —             | 82             | 2      | 6      | namecheap       |
| toneup.fans       | available | $13.98    | —             | 80             | 5      | 7      | namecheap       |
| hangon.fans       | available | $13.98    | —             | 82             | 6      | 7      | namecheap       |
| pierogi.fans      | available | $13.98    | —             | 82             | 7      | 7      | namecheap       |
| dogsick.fans      | available | $13.98    | —             | 90             | 1      | 7      | namecheap       |
| getlife.fans      | available | $13.98    | —             | 80             | 5      | 8      | namecheap       |
| headout.fans      | available | $13.98    | —             | 82             | 6      | 8      | namecheap       |
| beawake.fans      | available | $13.98    | —             | 84             | 3      | 8      | namecheap       |
| chaitea.fans      | available | $13.98    | —             | 86             | 3      | 8      | namecheap       |
| becalled.fans     | available | $9.88     | $9.88         | 86             | 2      | 9      | namesilo        |
| whynot.fans       | available | $13.98    | —             | 74             | 39     | 7      | namecheap       |
| tokens.fans       | resell    | —         | —             | 51             | 36     | 6      | Spaceship, Inc. |
| nets.fans         | premium   | $70       | $70           | 54             | 81     | 4      | namecheap       |
| commonground.fans | available | $13.98    | —             | 74             | 28     | 13     | namecheap       |
| regions.fans      | premium   | $69.99    | —             | 64             | 59     | 7      | name.com        |
| deeplearning.fans | available | $13.98    | —             | 74             | 23     | 13     | namecheap       |
| agents.fans       | premium   | $699.90   | —             | 56             | 50     | 6      | name.com        |
| CapeCod.fans      | available | $13.98    | —             | 78             | 22     | 8      | namecheap       |
| cars.fans         | premium   | $700      | $700          | 66             | 47     | 4      | namecheap       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,493 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fans?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fans?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .fans domains. That gives it a clear commercial profile: names built around fandom, audiences, creators, clubs, and community identity. Examples such as Acup.fans, dogsit.fans, edamame.fans, QandA.fans, and toneup.fans show a mix of playful dictionary terms, action phrases, and niche-interest words. For founders, the main question is whether the word is memorable and naturally fits a fan relationship. For investors, the key test is whether the term has clear end-user relevance at a low enough ask to leave room for resale. The median ask across this set is 120.43, so pricing discipline matters less than category fit and renewal tolerance.

- All names in this set use the .fans extension
- Median ask across the selection is 120.43
- Best fit is fan, creator, club, or audience branding
- Check word clarity, renewal fit, and trademark risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FANS One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FANS page](https://unique.domains/domains/tld/fans?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fans_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
