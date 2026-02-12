# Kentra Documentation

## Purpose
This repository is the public documentation entrypoint for Kentra.
It explains product value, platform capabilities, and adoption paths.
The content is written for customers, partners, and evaluators.
Architecture and security statements must stay consistent with source docs.
Every page should prioritize clarity, traceability, and stable terminology.
Use plain language first, then link to deeper technical references.
Keep wording reusable across marketing, platform, and product narratives.

## System Role
This repository supports the Kentra Web-App Platform communication layer.
It is not the authority for runtime product behavior or license decisions.
Domain logic and license authority belong to the Product-Core system.
Internal implementation and governance details stay in internal docs.
Public pages should reference authoritative internal documents when needed.
Keep boundaries explicit between marketing, platform, and product concerns.
Keep legal and compliance wording aligned with approved reference material.
Avoid publishing implementation assumptions without source-backed evidence.

## Quick Start
1. Define the audience and desired outcome before drafting a page.
2. Use consistent names: Product-Core, Web-App Platform, and UI Kit.
3. Explain user impact first, then link to deeper technical references.
4. Avoid speculative implementation details or roadmap-style promises.
5. Prefer short hub pages that route to focused deep-dive documents.
6. Keep all links relative and verify them within the same change.
7. Update neighboring index pages whenever a new page is introduced.
8. Keep glossary terms consistent across all navigation levels.
9. Add concise examples when a concept can be interpreted in multiple ways.
10. Use images only when they clarify a decision or workflow.
11. Keep filenames predictable for indexing and automation.

## Repository Layout
- `README.md`: repository entrypoint and documentation guardrails.
- Topic folders at root: main public docs grouped by domain.
- `assets/`: shared images, diagrams, and visual references.
- `reference/`: reusable definitions and cross-page reference material.
- One primary topic per file to avoid overlap and content drift.
- Keep naming readable and stable for automation and search.
- Keep page ownership and review responsibility clear in each folder.
- Keep cross-links focused and avoid circular navigation structures.
- Group audience-specific pages under dedicated hub documents.
- Place reusable snippets in shared reference files.

## Related Documentation
- Canonical system architecture:
  `../docs/engineering/architektur/system-architecture-canonical.md`
- Web-App scope and boundaries:
  `../docs/engineering/architektur/web-app/overview-and-scope.md`
- Product definition:
  `../docs/product/marke-und-produkt.md`
- Documentation governance:
  `../docs/governance/dokumentationsrichtlinien.md`
- Engineering governance:
  `../docs/engineering/governance/README.md`
- Internal documentation hub:
  `../docs/README.md`
- Engineering architecture hub:
  `../docs/engineering/architektur/README.md`
- Security and compliance hub:
  `../docs/engineering/security/README.md`
