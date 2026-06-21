# Course source material — Anthropic & OpenAI in the public sphere

Scraped content from the links in [`../analysis.md`](../analysis.md), organized into **high-level, company-agnostic topics** (education isn't split by lab — each topic file covers both OpenAI and Anthropic, labeled by source).

Scraped **2026-05-29** for the Konstanz AI & Public Governance course.

## Topics

| # | File | Covers | Labs with content |
|---|------|--------|-------------------|
| 1 | [01-education.md](01-education.md) | AI in (higher) education: products, partnerships, pedagogy, literacy | OpenAI + Anthropic |
| 2 | [02-government-and-public-sector.md](02-government-and-public-sector.md) | Gov offerings, federal partnerships, agency use cases | OpenAI (Anthropic = gap) |
| 3 | [03-nonprofits-and-public-good.md](03-nonprofits-and-public-good.md) | Philanthropy, community grants | OpenAI (Anthropic = gap) |
| 4 | [04-policy-governance-and-public-benefit.md](04-policy-governance-and-public-benefit.md) | Corporate governance, public-benefit structures, the Anthropic Institute | Anthropic (OpenAI = gap) |
| 5 | [05-societal-and-economic-impacts.md](05-societal-and-economic-impacts.md) | Research on labor, economy, societal effects | Anthropic (OpenAI = gap) |

> The original list had six sections; merging the two education sections (one per lab) into a single high-level topic yields **five** topic files, as you asked.

## Scrape quality notes

- **Scraped directly (high confidence):** all `anthropic.com` pages, the Harvard GSE article, the GSA press release, and the OpenAI Forum pages.
- **Reconstructed via web search (verify before publishing):** the four `openai.com` pages — ChatGPT Gov, OpenAI for Government, Solutions for Government, and the $50M fund — all returned HTTP 403 to automated fetching. Their content was rebuilt from search snippets of the same pages plus reputable secondary sources, and is flagged inline in each file.
- **Dynamic page:** the Anthropic Economic Index loads data client-side; only its framing was captured. Specific figures still need to be pulled from the live page.
- Some Anthropic pages carry **future-looking dates** (e.g., The Anthropic Institute dated Mar 11, 2026) — preserved as shown on the pages.

## Coverage gaps to fill for balance

Each topic file ends with cross-lab observations. The notable gaps (no link was in the source list) are flagged inline:
- **Government:** Anthropic's government offering (e.g., Claude Gov models, FedRAMP).
- **Nonprofits:** Anthropic's nonprofit/access programs.
- **Governance:** OpenAI's nonprofit-parent / PBC structure and charter.
- **Societal/economic:** OpenAI's economic-impact research.
