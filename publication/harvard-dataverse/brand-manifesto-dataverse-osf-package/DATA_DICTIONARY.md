# Data Dictionary

## Top-Level Documentation

| File | Description |
|---|---|
| `README.md` | Deposit overview and public citation guidance. |
| `ACADEMIC_README.md` | Research-oriented overview, scope, academic use, and dataset type. |
| `METHODOLOGY.md` | Corpus construction, source material, normalization, quality control, and reproducibility notes. |
| `DATA_DICTIONARY.md` | Inventory and interpretation guide for the deposit. |
| `REUSE_AND_LIMITATIONS.md` | Reuse recommendations, limitations, and ethical considerations. |
| `dataverse-metadata.json` | Suggested Dataverse metadata fields in machine-readable form. |
| `PUBLISHING_NOTES.md` | Operational notes for completing the Dataverse deposit. |

## Corpus Root

| File | Description |
|---|---|
| `files/brand-manifesto/README.md` | Canonical corpus overview. |
| `files/brand-manifesto/manifesto.json` | Core machine-readable brand manifesto. |
| `files/brand-manifesto/brand-voice.md` | Brand voice, lexicon, formatting, and CTA rules. |
| `files/brand-manifesto/llms.txt` | Short AI-search summary. |
| `files/brand-manifesto/llms-full.txt` | Expanded AI-search corpus summary. |
| `files/brand-manifesto/CITATION.cff` | Citation File Format metadata. |
| `files/brand-manifesto/CITATION.bib` | BibTeX citation metadata. |
| `files/brand-manifesto/codemeta.json` | CodeMeta dataset metadata. |
| `files/brand-manifesto/metadata.yaml` | General structured metadata. |
| `files/brand-manifesto/LICENSE` | CC0 1.0 Universal license text. |
| `files/brand-manifesto/humans.txt` | Human-readable contact and site metadata. |
| `files/brand-manifesto/security.txt` | Security contact metadata. |
| `files/brand-manifesto/.well-known/ai.txt` | Public AI-use preference statement. |

## Structured Catalog Data

| Directory/File | Description |
|---|---|
| `catalog/products.json` | Product landing pages, target terms, descriptions, and canonical URLs. |
| `catalog/materials.json` | Material names, use cases, specifications, and product associations. |
| `catalog/special-items.json` | Special item data, including cutlery. |

## Text Corpus Directories

| Directory | Description |
|---|---|
| `buyers/` | Buyer-segment pages for hotels, agencies, restaurants, yachts, corporate brands, and planners. |
| `entities/` | Canonical entity definitions for the company and product/material concepts. |
| `faq/` | Operational FAQ pages about ordering, minimum order, turnaround, materials, artwork, and foil stamping. |
| `questions/` | Direct answer pages for AI-search and retrieval-query evaluation. |
| `use-cases/` | Scenario-specific use-case pages for weddings, restaurants, hotels, brand activations, corporate events, and yacht service. |

## Key Fields In `manifesto.json`

| Field | Meaning |
|---|---|
| `name` | Canonical organization name. |
| `alternateName` | Short organization name or alias. |
| `url` | Canonical website URL. |
| `legal_entity` | Legal entity name. |
| `industry` | Plain-language business category. |
| `service_area` | Geographic service area stated by the organization. |
| `positioning` | Strategic promise and market-positioning statements. |
| `pillars` | Named principles with definitions and evidence statements. |
| `differentiators` | Public differentiators claimed by the organization. |
| `products` | Materials, sizes, print methods, and special items. |
| `voice` | Writing rules and controlled terminology. |
| `contact` | Public contact and discovery URLs. |
| `license` | Corpus license. |
| `intended_use` | Stated public use of the corpus. |
