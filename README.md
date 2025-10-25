1. question about this url, "https://www.youtube.com/watch?v=48pxVdmkMIE&t=374s", is this section "v=48px" random chance or does that mean a width in pixels?
2. this is just another url from a founder I saw while browsing, "https://www.youtube.com/watch?v=v0gjI__RyCY&t=14s"
3. I'm curious about how to set up the either, two wallets, or four wallets for me Chandler, and Zhandler.
4. We probably need to recieve some tokens from both the gwas.eth and zwas.eth ENS wallets.
5. when some work gets done that I've been chatting with chatgpt about on their website, then we are both to be rewarded for either of our work.
6. So maybe I nee the ENS zhandler.eth 


# README.md for gwas.ai

## Core Repo Structure (gwas-ai/gwas-ai/)

| File / Folder            | Purpose                         | Notes                                                                                       |
| ------------------------ | ------------------------------- | ------------------------------------------------------------------------------------------- |
| `README.md`              | Overview of **GWAS.ai**         | Acts as landing explainer and links to docs/wiki/sheets.                                    |
| `index.html` or `/docs/` | GitHub Pages root               | Either a generated site (from Deno/Next.js) or simple static page.                          |
| `.gwas/context.yaml`     | Local-first context metadata    | Defines domain links (api.gwas.ai, docs.gwas.ai, etc.), Sheets/Docs IDs, repo mapping, etc. |
| `.gitattributes`         | Text normalization              | Ensures line endings and diff formatting across domains.                                    |
| `.gitignore`             | Ignore build, cache, logs       | Include `/dist`, `/node_modules`, `/venv`, `/tmp`, etc.                                     |
| `LICENSE`                | Open license (e.g., MIT)        | Public visibility standard across the network.                                              |
| `CNAME`                  | Custom domain binding           | Should contain `gwas.ai` for GitHub Pages.                                                  |
| `_config.yml`            | Jekyll/GitHub Pages config      | Optional—helps Pages render Markdown correctly.                                             |
| `.github/workflows/`     | GitHub Actions                  | Automate deploys, mirror updates, or validation checks.                                     |
| `/src/` or `/site/`      | Source files                    | TS/HTML/CSS or Deno scripts generating your static site.                                    |
| `/public/`               | Assets (logos, images, favicon) | Mirror CDN structure (`cdn.gwas.ai`).                                                       |
| `/scripts/`              | Deno or CLI tools               | For updating `.gwas/context.yaml`, syncing sheets, etc.                                     |
| `/docs/`                 | Markdown docs                   | Could autogenerate from `doc.gwas.ai`.                                                      |
| `/data/`                 | Schema or JSON/CSV              | Base tables for “specification.csv” and derived datasets.                                   |
| `/feedback/`             | Feedback templates              | Aligns with `feedback.gwas.ai`.                                                             |
| `/meta/`                 | Metadata and snapshots          | e.g., `meta/today.yaml`, `meta/version.json`.                                               |

## Markdown Files

| File               | Role                                           |
| ------------------ | ---------------------------------------------- |
| `README.md`        | Intro, key links, mission summary              |
| `CONTRIBUTING.md`  | Defines PR and feedback process                |
| `CHANGELOG.md`     | Versioned updates per domain snapshot          |
| `ROADMAP.md`       | Short- and long-term goals                     |
| `DOMAINS.md`       | Table of all `gwas.*` + `zwas.*` mirrors       |
| `AGENTS.md`        | Mapping of “founders” / digital twin agents    |
| `SPECIFICATION.md` | Mirror of your central “specification.csv”     |
| `STRUCTURE.md`     | Directory schema and naming conventions        |
| `LICENSE.md`       | Optional if LICENSE file is short              |
| `CREDITS.md`       | Mentions AI/human contributors and linked orgs |
| `METADATA.md`      | Schema for `.gwas/context.yaml` fields         |


Jeff Dean & Noam Shazeer — 25 years at Google: from PageRank to AGI

Dwarkesh Patel
100 Founders chosen by me based on my opinion of their qaulities.
I have a hunch that they would both contribute and value contributing were they convinced of GWAS Labs - AI  Alignment strategy.
