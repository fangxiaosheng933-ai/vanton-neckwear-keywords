# Vanton Neckwear Keyword Repository

This repository is the working keyword evidence base for **Vanton Neckwear** Etsy listings.

## Purpose

Build Etsy titles and 13 tags from real product truth + market evidence + observed buyer search behavior, instead of choosing keywords from search volume alone.

## Evidence Layers

1. **MARKET DATA** — eRank / keyword-market metrics such as searches, clicks, CTR, competition and keyword difficulty.
2. **OBSERVED SEARCH TERMS** — real search phrases that have already brought visits to Vanton Neckwear listings in Etsy Stats.
3. **VALIDATED KEYWORDS** — terms promoted only after repeated real performance evidence (click/order/profit where available).

Observed terms are evidence, not automatic tags. Search volume is need evidence, not buyer need itself.

## Repository Structure

- `market-data/` — imported keyword datasets.
- `etsy-search-terms/` — real search terms observed in Etsy Stats.
- `rules/` — tag-selection and evidence-handling rules.
- `validated-keywords/` — keywords promoted after repeated performance validation.
- `listing-history/` — future listing-level keyword/test history.

## Default Tag Selection Flow

`PRODUCT TRUTH -> BUYER NEED -> OBSERVED SEARCH TERMS -> MARKET DATA -> SHARED INTENT -> 13 TAGS -> PUBLISH -> OBSERVE -> VALIDATE`

No keyword may override product truth. Irrelevant, trademark-risk, unsupported material/style/size, or wrong-product-type terms are excluded even if they generated traffic.

## Current Baseline

- Market dataset: `2026-09-07` Vanton Neckwear shop keyword export, 216 keyword rows.
- Observed buyer search terms: `2026-09-07` Etsy Stats screenshots, normalized and deduplicated into a working observed-search dataset.

This repository is intended to be updated whenever new Etsy Search Terms, eRank exports, listing performance data, or order evidence becomes available.
