# Available .VIP One-Word Domains (10,367)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C367%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .vip one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,367 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,367 domains · **Median ask:** $344.22 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/vip`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/vip?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./vip.csv">CSV</a> / <a href="./vip.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VIP search](https://unique.domains/domains/tld/vip?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VIP search](https://unique.domains/domains/tld/vip?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VIP one-word domain catalog.

### Files

- `vip.csv` — public CSV extract (1,000 rows)
- `vip.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/vip-oneword-domains/main/vip.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                               |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------- |
| forces.vip        | available | $10.98    | —             | 82             | 12     | 6      | namecheap                                               |
| open.vip          | resell    | —         | —             | 70             | 59     | 4      | Gname.com Pte. Ltd.                                     |
| Flowers.vip       | premium   | $3,500    | $21           | 72             | 39     | 7      | namecheap                                               |
| plated.vip        | available | $10.98    | —             | 66             | 11     | 6      | namecheap                                               |
| one.vip           | resell    | —         | —             | 84             | 50     | 3      | Gname.com Pte. Ltd.                                     |
| pages.vip         | premium   | $3,125    | —             | 52             | 28     | 5      | name.com                                                |
| panels.vip        | available | $4.99     | $19.49        | 48             | 11     | 6      | namesilo                                                |
| profile.vip       | resell    | —         | —             | 76             | 32     | 7      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| KFC.vip           | premium   | $7,000    | $21           | 74             | 27     | 3      | namecheap                                               |
| breaks.vip        | available | $10.98    | —             | 52             | 10     | 6      | namecheap                                               |
| heroes.vip        | resell    | —         | —             | 68             | 29     | 6      | Chengdu West Dimension Digital Technology Co., Ltd.     |
| bees.vip          | premium   | $218.75   | —             | 54             | 27     | 4      | name.com                                                |
| steroids.vip      | available | $4.99     | $19.49        | 50             | 10     | 8      | namesilo                                                |
| plug.vip          | resell    | —         | —             | 74             | 27     | 4      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| doctors.vip       | premium   | $3,125    | —             | 56             | 26     | 7      | name.com                                                |
| splits.vip        | available | $4.99     | $19.49        | 70             | 9      | 6      | namesilo                                                |
| trades.vip        | resell    | —         | —             | 71             | 26     | 6      | Sav.com, LLC - 22                                       |
| pops.vip          | premium   | $302.50   | $17.70        | 74             | 24     | 4      | namesilo                                                |
| determination.vip | available | $10.98    | —             | 70             | 9      | 13     | namecheap                                               |
| flights.vip       | resell    | —         | —             | 61             | 22     | 7      | Dynadot Inc                                             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,367 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/vip?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/vip?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .vip domains. The strongest names tend to be clear dictionary words, easy to say, and broad enough to support more than one use case. Examples here range from punchy terms like slip.vip and cover.vip to more abstract words like attitude.vip and qualitative.vip. With a median ask of $344.22 across 10,362 domains, the key question is not just price, but whether the word feels memorable, commercially flexible, and clean enough to justify the extension. When comparing these domains, prioritize clarity, recall, and whether the word still sounds credible with .vip attached.

- Prioritize clean, memorable words that fit naturally with .vip
- Compare ask price against word strength, not length alone
- Broad terms like cover.vip can age better than narrow phrases
- Check for trademark exposure before treating a name as ownable

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VIP One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VIP page](https://unique.domains/domains/tld/vip?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vip_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
