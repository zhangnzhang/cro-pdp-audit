# cro-pdp-audit

English | [简体中文](README.zh-CN.md)

An AI skill that audits an entire e-commerce product page for conversion: 12 sections scored out of 100, cross-page risk signals, and the 5 issues costing you the most sales — each with a concrete fix, in ROI order.

Give it a screenshot, a URL or a mockup. Works with Claude (as a Skill) and any agent that can read a Markdown instruction file.

## What it checks

| Section | Points | What it looks for |
|---|---|---|
| Hero / above the fold | 12 | Title, subheadline, first image, price, rating — answered in ~8 seconds |
| Image gallery | 12 | Close-ups, in-scale, in-context, customer photos, mobile carousel |
| Product video | 8 | Demo over brand ad, strong first 3 seconds, captions, placement |
| Benefit > feature copy | 15 | Outcomes, not specs; vitamin vs painkiller positioning |
| Social proof | 12 | Rating anchor, detailed and recent reviews, customer photos, believable averages |
| FAQ | 5 | Shipping, returns, fit, care, the category's big question |
| Trust & risk reversal | 8 | Visible returns, shipping clarity, guarantees, contact, honest scarcity |
| CTA & add to cart | 10 | Specific copy, sticky on mobile, contrast, risk line underneath |
| Design & hierarchy | 8 | Contrast, type size, hierarchy, whitespace, no horizontal tabs |
| Mobile | 5 | Speed, tap targets, zoom, pop-ups |
| Marketing hooks | 3 | Genuine scarcity, decoys, bundles — nothing fake |
| Upsell / cross-sell | 2 | Relevant "frequently bought together" with stated savings |

Plus seven 🟢🟡🔴 cross-page signals (category fit, consistency, audience match, localization, review recency, scannability, cognitive load), a rewrite table, and up to five next steps in ROI order. A 50-point quick-scan mode is included.

See a full [sample audit](examples/sample-audit.md).

## Why it's useful

- **Anchored scoring.** Every section has written anchors and standard deductions, so two audits of the same page come out close.
- **Evidence, not opinions.** A built-in evidence library — Baymard, Nielsen Norman Group, PowerReviews, Northwestern's Spiegel Research Center, BrightLocal, Stanford Web Credibility Research, VWO and Unbounce tests, WCAG and Apple guidelines — explains *why* each fix matters. Every figure has a source and a confidence tier.
- **No fake proof.** Rewrites use placeholders like `[real rating]` and `[real review count]`. The skill is told never to invent reviews, ratings, sales counts or press mentions.
- **Prioritized.** Five fixes, ranked by return, each executable as written.

## Install

**Claude:** copy `skills/cro-pdp-audit/` into `~/.claude/skills/` (or your project's `.claude/skills/`), then share a screenshot:

> Audit this product page for conversion.

**Other agents:** use `skills/cro-pdp-audit/SKILL.md` as the instructions; reference files load on demand.

## Files

```
skills/cro-pdp-audit/
├── SKILL.md                  # Workflow, output template, ground rules
└── references/
    ├── sections.md           # Scoring anchors for all 12 sections
    ├── evidence.md           # Research and published tests, with sources and confidence tiers
    └── checklist.md          # 50-point quick scan
examples/
└── sample-audit.md           # A full worked audit (fictional product)
```

## Evidence tiers

**A** — checked against the original source. **B** — named, credible source. **C** — widely repeated but hard to trace; the skill must say "commonly cited". Published results are presented as references, never as forecasts for your page. Found a better source? Open an issue.

## License

[MIT](LICENSE)
