---
version: 2025.06.15-a
last_updated: 2025-06-15
verified: true
---

# 🗺 MosaicAI docs.map.md

A reference map of all modular documents used by MosaicAI.

---

##  Strategy Modules

| ID | Description |
|----|-------------|
| `campaign.strategy.canvas` | Guides structured campaign strategy development |
| `brand.build.canvas`       | Constructs a modular brand system with core identity and output |
| `brief.write`              | Generates creative/comms briefs from upstream inputs |
| `brand.audit.canvas`       | Audits a brand’s strategic and tonal alignment using TESSERA |
| `campaign.audit.canvas`    | Reviews a past campaign’s effectiveness and brand consistency |
| `web.audit.canvas`         | Evaluates website clarity, UX, and tone alignment             |
| `social.audit.canvas`      | Diagnoses tone and visual coherence across social platforms   |
| `heuristic.review.canvas`  | Applies scorecard logic to review any asset heuristically      |

---

##  Intelligence Files

| ID | Description |
|----|-------------|
| `explainer.md`             | Core explainer for the TESSERA brand operating system |
| `brand_os.md`     | Full operating system document |
| `tessera_tone_of_voice_guidelines.md` | Voice calibration, tone sliders, and sample language |
| `mosaicai_command_codex_updated.md.md` | Command Codex |

---

## 📁 File Usage Notes

- These modules are **referenced dynamically** by MosaicAI during any brand/campaign session.
- Ensure filenames are consistent and reference IDs are declared inside the .md.

### mosaicai_instructions_enhanced.md
- Description: The primary instruction set for MosaicAI GPT, aligned with the Loop methodology and enhanced with strategic, narrative, design, and media frameworks.
- Use: Paste contents into Custom GPT Instructions or embed within the model’s system prompt.

- [Loop Reflect Canvas](#loop-reflect-canvas)
- [Proposal Build Canvas](#proposal-build-canvas)
| `archetype.evaluate.canvas` | Determines dominant brand archetypes using behavioural cues |