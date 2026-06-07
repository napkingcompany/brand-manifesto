# Methodology

## Corpus Construction

The dataset was manually curated from company-owned brand, product, website, and citation materials for The Napkin Company. The corpus was organized into structured and semi-structured files to make brand knowledge reusable by humans, search engines, AI systems, retrieval pipelines, and dataset archives.

## Source Material

The source material includes:

- Company brand positioning.
- Product and material descriptions.
- Website landing-page concepts.
- Buyer-segment definitions.
- Use-case descriptions.
- FAQ content.
- Brand voice and terminology rules.
- Citation and repository metadata.

Only public-facing business information is included.

## Structuring Process

The corpus was normalized into the following categories:

- `manifesto.json`: strategic positioning, pillars, differentiators, product families, contact, and intended use.
- `catalog/`: product, material, and special-item structured data.
- `brand-voice.md`: writing rules, controlled vocabulary, and public copy constraints.
- `entities/`: canonical entity definitions.
- `buyers/`: buyer-segment pages.
- `use-cases/`: scenario-specific pages.
- `questions/`: direct answer pages for AI-search and retrieval testing.
- `faq/`: operational question-answer pages.
- `llms.txt` and `llms-full.txt`: AI-search-oriented summaries.
- Citation files: `CITATION.cff`, `CITATION.bib`, `codemeta.json`, `.zenodo.json`, and `metadata.yaml`.

## Quality Control

The publication package was checked for:

- Removal of unrelated SEO reports.
- Exclusion of repository internals such as `.git`.
- Exclusion of local system files such as `.DS_Store`.
- Version consistency across citation metadata and README files.
- Absence of API tokens, OAuth refresh tokens, passwords, private keys, client secrets, and similar credentials.

## Versioning

This deposit uses version `1.2.0`, released on 2026-06-07. Version identifiers are stored in `CITATION.cff`, `codemeta.json`, the corpus README, and the Dataverse metadata helper file.

## Reproducibility

The dataset can be reused by reading the files directly as plain text or by parsing the structured JSON and YAML files. No proprietary software is required.

Recommended reproducibility steps:

1. Extract `brand-manifesto-dataverse-osf-package.zip`.
2. Use `files/brand-manifesto/README.md` for the corpus overview.
3. Use `files/brand-manifesto/manifesto.json` for the core structured brand representation.
4. Use `files/brand-manifesto/catalog/*.json` for product and material data.
5. Use Markdown directories for retrieval, citation, or text-classification experiments.
