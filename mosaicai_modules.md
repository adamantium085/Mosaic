---
version: 2025.06.15-a
last_updated: 2025-06-15
verified: true
---

# 📚 MosaicAI Modules Bundle (Combined)

## 🔗 Index
- [Loop Reflect Canvas](#loop-reflect-canvas)
- [Brand Build Canvas](#brand-build-canvas)
- [Brief Write Canvas](#brief-write-canvas)
- [Campaign Strategy Canvas](#campaign-strategy-canvas)
- [Campaign Brief Intake](#campaign-brief-intake)
- [Loop Init Canvas](#loop-init-canvas)
- [Mockups Request Canvas](#mockups-request-canvas)
- [Output Prepare Canvas](#output-prepare-canvas)
- [Persona Audit Canvas](#persona-audit-canvas)
- [Brand Audit Canvas](#brand-audit-canvas)
- [Campaign Audit Canvas](#campaign-audit-canvas)
- [Web Audit Canvas](#web-audit-canvas)
- [Social Audit Canvas](#social-audit-canvas)
- [Heuristic Review Canvas](#heuristic-review-canvas)

---

## 📘 Module: Brand Build Canvas

#  MosaicAI Module: brand.build.canvas

###  Purpose
Collaboratively guide the creation of a brand foundation using modular, interactive input.

---

##  Input Branches

### 1. Brand Core
- Brand name
- Industry / category
- Vision and mission
- Positioning

### 2. Audience
- Target segments
- Pain points and Jobs To Be Done
- Competitive awareness

### 3. Archetype
- Select or infer one of 12 brand archetypes
- Emotional tone and motivation

### 4. Tone of Voice
- Calibrate based on 5 TESSERA tone sliders
- Intelligent / Witty / Clear / Confident / Creative

### 5. Visual System
- Logo type
- Colour palette
- Typography
- Image treatment preferences
- Visual signature examples

---

##  Output Structure

```markdown
## Brand OS: {Brand Name}

### 🧱 Core
- Vision:
- Mission:
- Category:

### 🧍 Audience
...

### 🧙 Archetype
...

### 🎤 Tone
...

### 🎨 Visual System
...
```

---

##  Loop Phase
**Phase: Intelligence → Strategy**

---

## 🤖 MosaicAI Meta-Trigger
- `brand.build.canvas()`
- Prompt: “Can you help me build a brand?”


---

## 📘 Module: Brief Write Canvas

#  MosaicAI Module: brief.write.canvas

###  Purpose
Generate structured communication and creative briefs using upstream inputs from the brand and campaign strategy phases.

This canvas ensures outputs align with:
- Brand archetype
- Target audience
- Campaign objectives
- Channel constraints
- Tone of voice (per TESSERA)

...

## 🤖 MosaicAI Meta-Trigger
This module can be activated by:
- `brief.write(canvas=True)`
- "Can you write me a creative brief for this campaign?"

Also triggered post-campaign or brand generation if `brief_required = True`


---

## 📘 Module: Campaign Strategy Canvas

# 📊 MosaicAI Module: campaign.strategy.canvas

###  Purpose
Guide clients through campaign strategy development with modular input capture, including goals, audience, channels, and brand assets.

---

##  Input Branches

### 1. Brand Readiness Check
- Do you have brand assets?
  - If **Yes**, prompt for uploads:
    - Logo (SVG or high-res PNG)
    - Brand Guidelines (PDF or Figma link)
    - Tone of Voice documentation
    - Recent campaigns or pitch decks
  - If **No**, trigger: `brand.build.canvas()`

### 2. Campaign Objectives
- What is the goal of this campaign?
- Are there specific products, services, or launches to feature?

### 3. Target Audience
- Primary and secondary audience groups
- Demographic or psychographic notes

### 4. Channel Strategy
- Planned platforms (Instagram, LinkedIn, Email, OOH)
- Media constraints or specs (e.g. 9:16, 1200x1200)

### 5. Timeline
- Launch date or window
- Key milestones or dependencies

---

##  Output Structure

```markdown
## Campaign Strategy Brief

###  Objective
...

###  Audience
...

###  Channels
...

### 🗓 Timeline
...

###  Assets Needed
...
```

---

##  Loop Phase
**Phase: Strategy → Activation**

---

## 🤖 MosaicAI Meta-Trigger
- `campaign.strategy.canvas()`
- Prompt: “Can you help me plan a campaign?”


---

## 📘 Module: Campaign Brief Intake

# 📥 Campaign Brief Intake

This document is used to collect structured inputs **before** generating a campaign plan using `campaign.strategy.canvas()`.

---

## 🧰 Brand Context

**Brand Name:**  
**Product/Service:**  
**Industry:**  
**Core Positioning / USP:**  
**Existing Brand Materials (optional):** Logo, Tone of Voice, Visual Guidelines

---

## 🎯 Campaign Goals

**What are we trying to achieve?**  
- Awareness / Reach  
- Lead generation  
- Sales / Conversion  
- Product launch  
- Other: ___________

**Is this tied to a specific timeframe or event?**  
e.g. seasonal campaign, product drop, store opening.

---

## 👥 Target Audience

**Primary Segment(s):**  
**Demographics or Psychographics (if known):**  
**Key Pain Points or Desires:**  
**What language or visuals resonate with them?**  

---

## 📊 Key Messaging & Offer

**What’s the core message you want to communicate?**  
**Any offers, pricing, hooks or deadlines?**  
**Compliance or legal language that must be included?**  

---

## 📁 Supporting Materials

**What past campaigns might inform this one?** _(if any)_  
- [ ] Past campaign results (e.g. CTRs, conversions, awareness uplift)  
- [ ] Visual assets (finished art, mockups)  
- [ ] Ad copy or headlines that worked well  
- [ ] Landing pages / emails used  
- [ ] Other relevant data

**Where can this info be sourced from?**  
e.g. Google Drive folders, analytics dashboards, team references.

**What’s Worked Before:**  
Examples:  
- A UGC-style reel outperformed branded ads by 2x CTR  
- “Minimal luxury” visual style had strongest engagement last time

---

## 📣 Media / Channels

**Preferred or mandatory channels:**  
- [ ] Meta (FB/IG)  
- [ ] TikTok  
- [ ] Google Ads  
- [ ] Email  
- [ ] Print / OOH  
- [ ] Website / Landing Page  
- [ ] Other: ___________

**Budget or constraints (optional):**  

---

## ✅ Admin & Owners

**Who’s running this campaign?**  
**Who approves creative / final outputs?**  
**Deadlines:**

---

## 📘 Module: Loop Init Canvas

#  MosaicAI Module: loop.init.canvas

###  Purpose
Kickstart a full MosaicAI engagement by establishing foundational memory...

...

## 🤖 MosaicAI Meta-Trigger
- `loop.init(project="Brand Refresh for Horizon Foods")`
- Triggered by prompt: "We're starting a brand project, can you set this up?"
- Also offered if conversation begins without clear context


---

## 📘 Module: Mockups Request Canvas

# 🎨 MosaicAI Module: mockups.request.canvas

###  Purpose
Support creative prototyping and visual layout guidance across campaign formats...

...

## 🤖 MosaicAI Meta-Trigger
- `mockups.request(format="instagram carousel")`
- Prompts like: "What would this look like as a LinkedIn ad?"
- Follows post-brief if deliverables include visual assets


---

## 📘 Module: Output Prepare Canvas

#  MosaicAI Module: output.prepare.canvas

###  Purpose
Package deliverables across brand, campaign, and creative phases into structured, client-ready output formats.

...

## 🤖 MosaicAI Meta-Trigger
- `output.prepare(deliverables=[...])`
- Prompt like: "Package this for client delivery"
- Also triggered post-mockup or final asset generation phase


---

## 📘 Module: Persona Audit Canvas

#  MosaicAI Module: persona.audit.canvas

###  Purpose
Assess the quality, completeness, and strategic fit of an existing persona...

...

## 🤖 MosaicAI Meta-Trigger
Activated by:
- `persona.audit(canvas=True)`
- Uploading a persona file
- Prompts like "is this persona complete?", "can you check this persona for tone fit?"


---

## 📘 Module: Brand Audit Canvas

# 📊 MosaicAI Module: brand.audit.canvas

### Purpose
Evaluate a brand’s foundational coherence...

---

## 📘 Module: Campaign Audit Canvas

# 📊 MosaicAI Module: campaign.audit.canvas

### Purpose
Review and evaluate previous or current campaigns...

---

## 📘 Module: Web Audit Canvas

# 🌐 MosaicAI Module: web.audit.canvas

### Purpose
Evaluate a brand’s website for strategic clarity...

---

## 📘 Module: Social Audit Canvas

# 📱 MosaicAI Module: social.audit.canvas

### Purpose
Evaluate a brand’s social media presence...

---

## 📘 Module: Heuristic Review Canvas

# 🧮 MosaicAI Module: heuristic.review.canvas

### Purpose
Evaluate a creative or strategic asset...
---

## 📘 Module: Proposal Build Canvas

# 📄 MosaicAI Module: proposal.build.canvas

### Purpose
Transform strategic insight and diagnostic findings into a structured proposal for client presentation, approval, or internal planning.

This canvas bridges MosaicAI’s audit and strategy outputs with real-world scoping — enabling deliverables, costs, timelines, and logic to be framed into an actionable project brief or pitch document.

---

## 🧾 Input Branches

### 1. Context
- Brand or project name
- Objective of the proposal (pitch, retainer, scoped sprint)
- Type: Campaign / Brand / Diagnostic / Creative Ops / Other

### 2. Modules to Include
- Suggested from upstream audit(s) or manually selected
- Allow user to select from a checklist:
  - brand.build.canvas
  - brief.write.canvas
  - mockups.request.canvas
  - campaign.strategy.canvas
  - output.prepare.canvas
  - Custom deliverables

### 3. Deliverables Map
- List of creative or strategic outputs proposed
- Format: slides, visuals, documents, campaigns, mockups, workshops

### 4. Timeline
- Start and end dates
- Sprint model (e.g. 2-week creative loop)
- Key delivery checkpoints

### 5. Investment/Cost Framing
- Total investment or estimate
- Optional: line-item or phase-based cost breakdown
- Optional: modular or tiered pricing

---

## 📦 Output Structure

```markdown
## 📄 Project Proposal: {{Project Name}}

### Objective
...

### Deliverables
- Strategic:
  - ...
- Creative:
  - ...
- Output formats: PDF, Figma, HTML, etc.

### Timeline
...

### Investment
...

### Notes & Next Steps
- Approval pathway
- Kickoff readiness
- Attached reference audits (if any)
```

---

## 🔁 Loop Phase
**Phase: Optimisation → Assembly**

---

## 🤖 MosaicAI Meta-Trigger

Activated by:
- proposal.build(canvas=True)
- Prompts like:
  - “Can you draft a proposal for this?”
  - “Summarise this audit into a scoped project.”
  - “Build me a Gantt or investment breakdown.”

Also triggered if:
- Prior audits or output.prepare.canvas exist without follow-up

---

## 🧪 Example Output (TESSERA-Compliant Proposal)

```markdown
## 📄 Project Proposal: Altitude Supply Co. – Brand Repositioning & Campaign Activation

---

### 🌀 TESSERA Loop-Aligned Structure

---

## 1. Intelligence – Strategic Clarity & Audit Foundations

This proposal is based on a full diagnostic phase, including:
- ✅ Completion of brand.audit.canvas
- ✅ Completion of campaign.strategy.canvas
- ✅ Access to existing brand guidelines
- ✅ Access to previous campaign performance summaries
- ✅ Stakeholder interviews via loop.init.canvas

---

## 2. Creative – Identity, Messaging & Experience Systems

Deliverables:

| Output | Description | Rounds of Revision |
|--------|-------------|--------------------|
| Creative Brief | Brand voice & messaging anchors | 2 |
| Campaign Core Concept | Narrative structure & tagline sets | 2 |
| Mockups x3 | IG Carousel, Hero Landing, Display Ad | 2 |
| Tone Reference Sheet | Visual & verbal identity alignment | 2 |

---

## 3. Activation – Campaign Deployment Plan

Rollout Ownership:
TESSERA will lead asset delivery and staging for digital channels, but media buying is client-led.

Channel Focus:
- Instagram (organic & paid)
- Display (retargeting & awareness)
- Web landing (conversion & storytelling)

Activation Plan:
- Creative handoff: Week 3
- Campaign kickoff: Week 4
- Launch support window: 2 weeks post-deploy

---

## 4. Optimisation – QA, Tuning & Timing

Launch & Evaluation Timing:
- Launch Date: July 12
- Midpoint QA: July 22
- Final wrap: August 2

Refinement Windows:
- Asset testing on landing page variants (v1.0 vs v2.0)
- Social performance reporting for first 10 days

---

## 5. Insight – Feedback Loop & Continuous Learning

Following the campaign, we will activate a loop.reflect.canvas process to extract insights across:
- Audience response
- Message fit
- Creative resonance
- Platform behavior

---

## 📅 Timeline Overview

| Week | Milestone                        |
|------|----------------------------------|
| W1   | Strategic Finalisation           |
| W2   | Creative Concept & Asset Drafts  |
| W3   | Revisions & Activation Prep      |
| W4   | Launch + Early QA Window         |

---

## 💸 Investment Summary

Flat Fee: £7,800
Includes: All deliverables, activation support, feedback loop management

Terms:
- 50% upon approval
- 50% upon delivery

---

## 🔄 Next Steps

- Confirm scope and approval
- Schedule internal kickoff call
- Begin creative development (Monday)
```

---

## 📘 Module: Loop Reflect Canvas

# 📄 MosaicAI Module: loop.reflect.canvas

### Purpose
To extract learnings, assess brand/project performance, and identify opportunities for evolution. This module captures insights at the end of a campaign or delivery, then loops them forward into new strategy or proposals.

---

## 🧾 Input Branches

### 1. Context
- Project or campaign name
- Launch and end dates
- Original objective or intended outcome

### 2. Data & Feedback Inputs
- Performance metrics (engagement, CTR, sales, signups)
- Qualitative feedback (client/team notes, audience sentiment)
- Pre/post audit comparison if available
- Timing & delivery performance

### 3. Insight Categories
- What worked well
- What underperformed
- Patterns or emerging signals
- Brand consistency feedback
- Speed, QA, and communication quality

---

## 🔍 Reflection Prompts

MosaicAI asks:
- Did this meet its original goal?
- Did the work match the brand voice and visual tone?
- Were assets performant by channel?
- What feedback was received?
- What would we do differently next time?

---

## 📦 Output Structure

```markdown
## 🪞 Post-Project Reflection: {{Project Name}}

### Objective Recap
...

### Success Metrics
...

### What Worked
...

### What Could Improve
...

### Insights & Opportunities
...

---

## Evolution Pathways

→ Recommend:
- New proposal (link to proposal.build.canvas)
- Brand asset updates
- Voice or design refinement
- Next campaign logic
```

---

## 🔁 Loop Phase
**Phase: Insight → Intelligence**

### 🔄 Loopback Trigger
This canvas feeds directly into `loop.init.canvas` by updating MosaicAI's intelligence state. Insights are carried forward into future campaigns or brand evolutions.

---

## 💼 Proposal Trigger Logic

If MosaicAI identifies actionable improvements, it can:
- Draft a scoped follow-up using `proposal.build.canvas`
- Summarise key upgrades to propose
- Create a light-weight evolution plan if preferred

This ensures the client receives forward motion, not just retrospective review.

---

## 🤖 MosaicAI Meta-Trigger

Activated by:
- `loop.reflect(canvas=True)`
- Prompts like:
  - “What did we learn from this?”
  - “Can you generate a post-campaign summary?”
  - “Should we improve anything?”

Also auto-triggered:
- On marking a project as complete
- After campaign.audit.canvas or output.prepare.canvas

# 📦 `archetype.evaluate.canvas.md`

```markdown
---
canvas: archetype.evaluate.canvas
loop_phase: Intelligence
trigger: optional
tags: [brand, identity, strategy]
---

## Purpose
Evaluate a brand’s core personality alignment through archetypal modeling to determine its behavioral orientation, emotional posture, and potential communication strategy.

## Usage Conditions
- Use when a brand audit reveals tone, behavior, or messaging cues that suggest a clear archetypal pattern.
- May be prompted manually or triggered by `brand.audit.canvas`.

## Inputs
- Website content, brand guidelines, key messages
- Audit outputs (optional)
- Any known internal voice documentation

## Brand Archetype Reference

Mosaic considers the following 12 archetypes:

1. **The Innocent** – Optimistic, honest, hopeful  
2. **The Everyman** – Relatable, down-to-earth, humble  
3. **The Hero** – Courageous, bold, achievement-driven  
4. **The Outlaw** – Disruptive, rebellious, provocative  
5. **The Explorer** – Independent, curious, adventurous  
6. **The Creator** – Imaginative, inventive, expressive  
7. **The Ruler** – Authoritative, responsible, organized  
8. **The Magician** – Visionary, transformative, inspired  
9. **The Lover** – Passionate, warm, empathetic  
10. **The Caregiver** – Supportive, nurturing, compassionate  
11. **The Jester** – Playful, humorous, light-hearted  
12. **The Sage** – Knowledgeable, analytical, wise

## Output Structure
- **Primary Archetype Identified**
- **Supporting Archetypes** (if present)
- **Key Evidence/Signals**
- **Strategic Implications** (for voice, activation, or creative)
- **Potential Risks** (if inconsistent)

## Method
Mosaic should:
1. Compare brand tone/behavior with the above archetypes
2. Select the most dominant match based on observed expression
3. Recommend voice, visuals, and actions that align with that archetype
4. Flag any divergence between declared identity and perceived archetype

## Example Output

**Primary Archetype:** Explorer  
**Supporting Archetype(s):** Sage  
**Evidence:**  
- Repetition of "freedom", "independence", "journey" in website copy  
- Visuals use vast spaces, earthy tones, minimal constraints  

**Strategic Implications:**  
- Messaging should emphasize autonomy and bold movement  
- Avoid language that implies confinement, control, or rigidity  

**Risks:**  
- Overuse may isolate conservative buyers  
- If visuals shift toward mainstream, mismatch may confuse audience

## Follow-up Triggers
- May prompt updates to `tone.of.voice.canvas`  
- Suggest refinement of `brand.build.canvas` to reflect archetypal cohesion  
```