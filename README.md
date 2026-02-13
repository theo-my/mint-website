# MINT Lab Website — GitHub Pages Migration

## Goal

Migrate mintresearch.org from Squarespace to a static site hosted on GitHub Pages. Squarespace subscription expires **Feb 14, 2026**.

## Domain

- **Domain**: mintresearch.org
- **Registrar**: Squarespace (remains as registrar even after site expires)
- **New hosting**: GitHub Pages (theo-my/mint-website initially, transfer to MINT org later)

## Phases

### Phase 1: Emergency (Feb 13) ← NOW
- [x] Extract all site content (text, structure, people, publications)
- [ ] wget full site backup (HTML, CSS, images, JS)
- [ ] Squarespace XML export
- [ ] Create WIP placeholder page
- [ ] Deploy to GitHub Pages
- [ ] Point domain to GitHub Pages

### Phase 2: Full Rebuild (Feb 14+)
- [ ] Design new static site (HTML/CSS, no framework needed)
- [ ] Migrate all content from extraction
- [ ] Team directory (60 people)
- [ ] Research themes (4 areas)
- [ ] Publications
- [ ] Impact/events
- [ ] Join MINT (PhD, fellowships, honours)
- [ ] Contact page
- [ ] Review with Seth

## Key Files

| File | Purpose |
|:-----|:--------|
| `content-extraction.md` | Full site content extracted from Squarespace |
| `backup-plan.md` | Squarespace backup strategy and commands |
| `docs/` | GitHub Pages source (published directory) |
| `docs/index.html` | Live site entry point |

## Organization

- **MINT Lab** = Machine Intelligence and Normative Theory Lab
- **Parent**: School of Philosophy, Australian National University
- **PI**: Professor Seth Lazar
- **Email**: mint@anu.edu.au
- **Twitter**: @mintresearchlab
