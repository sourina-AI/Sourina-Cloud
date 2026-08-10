# AI Email Workflow

> One pipeline from first draft to send-ready — three purpose-built AI skills merged into a single email journey. An **AI Email Studio** composes the email, a **Narrative Testing Engine** pressure-tests the message against named buyer personas, and an **Email QA Agent** runs 50+ pre-flight checks and scores launch readiness.

**Live case study →** [sourina-ai.github.io/Sourina-Cloud/Sourina_EmailAIWorkflow.html](https://sourina-ai.github.io/Sourina-Cloud/Sourina_EmailAIWorkflow.html)

---

## About

This is a single-page portfolio case study on **AI Email Workflow** — a unified email-operations pipeline I designed to take a marketing email from brief to send without dropping quality at any step. It merges three AI skills into one journey, so every email is **composed, validated against real buyers, and pre-flight-checked** before a single send.

Part of my **Sourina-Cloud** portfolio, alongside [The Narrative Testing Engine](https://sourina-ai.github.io/Sourina-Cloud/project_narrative_testing_engine.html).

## The journey — 3 skills, 4 moves

| Stage | Skill | What happens |
|---|---|---|
| **01 · Compose** | Email Studio | AI drafts a responsive, brand-safe HTML email — copy, blocks, tokens, CTA — from a short brief. |
| **02 · Validate** | Narrative Testing Engine | 11 named personas react, score the message honestly, name the competitor wedge, and hand back a ready-to-ship rewrite. |
| **03 · Pre-flight** | Email QA Agent | 50+ automated checks across HTML, links, compliance & content → a 0–100 launch-readiness score (PASS / WARNING / FAIL). |
| **→ Ship** | Launch | Only send-ready, on-message, on-brand email leaves the pipeline. |

```
compose  →  validate  →  pre-flight  →  launch
Studio       Testing        QA          ✓ send-ready
   ↑____________|______________|   (findings loop back)
```

It's a closed loop, not a straight line — weak copy flagged in Testing and failed checks in QA feed back into the Studio until the email clears every gate.

## What each stage does

**01 · Email Studio — compose**
- Brief → email in one pass: subject, preheader, body and CTA
- Modular, brand-safe blocks on Outlook-safe tables with dark-mode fallbacks
- Personalization tokens (`{{first_name}}`, `{{product}}`) and dynamic content blocks
- Exports clean, portable HTML that the next two stages consume

**02 · Narrative Testing Engine — validate**
- 11 named Adobe buyer personas across Decision Makers, Evaluators & End Users
- 4 honest scores per persona: resonance · clarity · win probability · future resonance
- Names the competitor wedge — Cornerstone, Docebo, Workday Learning, LinkedIn Learning, 360Learning, Absorb, Litmos
- 2026 AI-inbox-aware open-rate / CTR predictions; a one-shot rewrite plus 2 variants, saved to a Narrative Library

**03 · Email QA Agent — pre-flight**
- 50+ checks across 5 categories: HTML & rendering (9), links (8), stakeholder compliance (8), content (8), subject line (9)
- Launch readiness 0–100 (−10 per error, −5 per warning) → **PASS / WARNING / FAIL**
- Full audit history with JSON export

## Tech

- **Email Studio** — AI generation · responsive HTML · Outlook-safe tables · personalization tokens
- **Narrative Testing Engine** — React · FastAPI · Azure OpenAI (JSON mode) · localStorage Narrative Library
- **Email QA Agent** — Python · Flask · SQLAlchemy · SQLite · vanilla JS · REST API

The showcase itself is a single, dependency-free [`Sourina_EmailAIWorkflow.html`](Sourina_EmailAIWorkflow.html) — no build step, no external scripts.

---

*Internal / portfolio project. Product names and personas are used illustratively.*
