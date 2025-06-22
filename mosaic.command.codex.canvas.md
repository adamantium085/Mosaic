---
title: mosaic.command.codex.canvas.md
status: active
type: system
phase: universal
---

# Mosaic Command Codex Canvas

This canvas defines the command structure for operating Mosaic across the full TESSERA Brand OS lifecycle. It enables structured, modular, and predictable AI prompting through standardized trigger phrases.

---

## 🧠 INTELLIGENCE PHASE

| Command | Description |
|--------|-------------|
| `/summarise` | Run `data.summarization.canvas` on input data (e.g., Slack threads, interviews, surveys). |
| `/audit brand` | Run `brand.audit.canvas` — requires current brand file. |
| `/audit competitors` | Run `competitor.audit.canvas` — requires list of competitors. |
| `/scan market` | Trigger `market.scan.canvas` — requires audience or category scope. |
| `/detect trends` | Activate `trend.analysis.canvas` for macro and micro insight capture. |

---

## 🎯 STRATEGY PHASE

| Command | Description |
|---------|-------------|
| `/build proposal` | Run `proposal.build.canvas` based on summarized insights or uploaded data. |
| `/recommend kpis` | Run `metrics_framework.canvas` using client goals or OKRs. |
| `/apply frameworks` | Load `reference.frameworks.canvas.md` to inject STP, VoC, SWOT, or others. |
| `/retrain mosaic` | Trigger `mosaic.training.canvas.md` if Mosaic needs recalibration. |

---

## 🎨 CREATIVE PHASE

| Command | Description |
|---------|-------------|
| `/write brief` | Run `brief.write.canvas` based on proposal or strategic doc. |
| `/calibrate tone` | Use `tone.of.voice.canvas` — accepts example content for matching. |
| `/map archetype` | Run `archetype.mapping.canvas` — outputs brand personality logic. |
| `/mockup prompt` | Trigger `mockups.request.canvas` to auto-generate creative prompt language. |

---

## 🚀 ACTIVATION PHASE

| Command | Description |
|---------|-------------|
| `/prepare output` | Run `output.prepare.canvas` for export packaging. |
| `/qa checklist` | Generate preflight deployment checklist by platform or channel. |

---

## 📈 INSIGHT PHASE

| Command | Description |
|---------|-------------|
| `/reflect` | Use `loop.reflect.canvas` to summarise campaign learnings. |
| `/optimize` | Suggest next steps or improvements based on results. |
| `/loopback` | Trigger new Intelligence phase based on learnings. |

---

## ⚙️ MODIFIERS

| Modifier | Function |
|----------|----------|
| `--lite` | Run minimal output, summary-only. |
| `--deep` | Full-length output with reasoning, references, and next steps. |
| `--compare [X] [Y]` | Mosaic compares two strategies/briefs/etc. |
| `--custom [framework]` | Specify a framework to use (e.g., `--custom Blue Ocean`) |
| `--tone [example]` | Adjust output tone using input reference text. |

---

## 🔁 Integration Notes

- These commands are NOT input prompts for users. They are operational triggers Mosaic can recognize and interpret as instruction format standards.
- Mosaic may self-reference this canvas using: `mosaic.command.codex.canvas.md`
- For routing logic, see: `canvases.index.md`
- For full context and fallback behavior, reference: `guardrails.md`, `reference.frameworks.canvas.md`, and `tessera.docs.map.md`

---

## ✅ Summary

The Codex provides Mosaic and all human collaborators a shared protocol for interaction.

It reduces ambiguity, increases modularity, and supports outcome-driven reasoning.

