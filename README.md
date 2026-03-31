# henry-context-brain

Personal protocol and skill library for AI-assisted work.

Files in this repository are fetched at runtime by Claude and other AI agents. This is the **execution layer** — structured `.md` files that agents run, not read.

Reference context, brand docs, and working files live separately in Google Drive.

---

## How to use

Paste the raw URL of any file into your AI session before starting a task:

```
https://raw.githubusercontent.com/gwaiblade/henry-context-brain/main/protocols/CANON_INVESTMENT_market-screener.md
```

Then instruct the agent:

> "Fetch and follow this protocol before starting."

---

## Structure

```
henry-context-brain/
├── protocols/
│   └── CANON_INVESTMENT_market-screener.md
└── skills/
```

### Protocols
Multi-step workflows that orchestrate a complete job. Each protocol has a clear trigger, steps, and defined output.

### Skills
Reusable techniques called mid-task by protocols or directly by the agent. A skill does one thing well.

---

## File naming convention

```
CANON_[DOMAIN]_[descriptor].md
```

**Protocols:**
```
CANON_INVESTMENT_market-screener.md
CANON_CONTENTDESIGN_amazon-listing-build.md
```

**Skills:**
```
SKILL_INVESTMENT_arc-score-calculation.md
SKILL_WRITING_executive-summary.md
```

**Domains in use:**
- `INVESTMENT` — portfolio, screening, market research
- `WRITING` — communication, summaries, analysis
- `DESIGN` — visual, image, composition (Cranberry AI repo)
- `CONTENTDESIGN` — Amazon, ecommerce content (Cranberry AI repo)

---

## What lives here vs elsewhere

| Content | Location |
|---|---|
| Protocols + Skills | This repo |
| Brand context, personal briefs | Google Drive → Context-Brain |
| Working documents | Google Drive → Working |
| Final outputs | Google Drive → Final |

---

## Status

🟢 Active — updated as new protocols and skills are built.
